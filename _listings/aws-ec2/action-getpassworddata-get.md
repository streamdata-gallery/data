---
swagger: "2.0"
info:
  title: AWS EC2 API Get Password Data
  version: 1.0.0
  description: Retrieves the encrypted administrator password for an instance running
    Windows.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetPasswordData:
    get:
      summary: Get Password Data
      description: Retrieves the encrypted administrator password for an instance
        running Windows
      operationId: getpassworddata
      parameters:
      - in: query
        name: Attribute
        description: The name of the attribute
        type: string
      - in: query
        name: BlockDeviceMapping.N
        description: "Modifies the DeleteOnTermination attribute for volumes\t\t\t\tthat
          are currently attached"
        type: string
      - in: query
        name: DisableApiTermination
        description: If the value is true, you can't terminate the instance using
          the Amazon EC2      console, CLI, or API; otherwise, you can
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EbsOptimized
        description: Specifies whether the instance is optimized for EBS I/O
        type: string
      - in: query
        name: EnaSupport
        description: Set to true to enable enhanced networking with ENA for the instance
        type: string
      - in: query
        name: GroupId.N
        description: '[EC2-VPC] Changes the security groups of the instance'
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: InstanceInitiatedShutdownBehavior
        description: Specifies whether an instance stops or terminates when you initiate
          shutdown from the instance (using the operating system command for system
          shutdown)
        type: string
      - in: query
        name: InstanceType
        description: Changes the instance type to the specified value
        type: string
      - in: query
        name: Kernel
        description: Changes the instance's kernel to the specified value
        type: string
      - in: query
        name: Ramdisk
        description: Changes the instance's RAM disk to the specified value
        type: string
      - in: query
        name: SourceDestCheck
        description: Specifies whether source/destination checking is enabled
        type: string
      - in: query
        name: SriovNetSupport
        description: Set to simple to enable enhanced networking with the Intel 82599
          Virtual Function interface for the instance
        type: string
      - in: query
        name: UserData
        description: Changes the instance's user data to the specified value
        type: string
      - in: query
        name: Value
        description: A new value for the attribute
        type: string
      responses:
        200:
          description: OK
      tags:
      - password data
definitions: []
x-collection-name: AWS EC2
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---