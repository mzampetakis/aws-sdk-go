### SDK Features

### SDK Enhancements

### SDK Bugs

* `service/ec2`: Fix WaitUntilNetworkInterfaceAvailableWithContext not waiting when NetworkInterface ID not found
    * Fixes the ec2 WaitUntilNetworkInterfaceAvailableWithContext waiter to wait when InvalidNetworkInterfaceID.NotFound is received instead of failing.
