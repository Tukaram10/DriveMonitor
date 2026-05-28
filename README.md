6. Create Windows Service

Open CMD as Administrator:

sc create BlacklistTrunService binPath= "D:\BlacklistService\DriveMonitorService.exe"
start= auto

Start Service:

sc start BlacklistTrunService

Stop Service:

sc stop BlacklistTrunService

Delete Service:

sc delete BlacklistTrunService
