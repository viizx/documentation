# Create New Connection

If you wish to create a new connection, navigate to the <code>Connections</code> tab in the sidebar and click the <code>Create Connection</code> button.

<p><img src="/images/dashboard/connections/create-connection-1.png" alt="Create connection button" class="width-90"/></p>

After a new window shows up, you will be asked to provide the following details:

- **Connection name** – Name of the new connection
- **Type** – Connection type
- **Hostname** – The hostname or IP address of your remote server.
- **Username** – The username on your remote server
- **Initial dir** – The directory path you want to access at the remote server
- **Timeout** - The connection timeout setting measured in seconds

If you select SSH as your desired connection type, additional you will have to provide additional info:

- **Authorization** – The authorization method you want to use for connecting to the remote server
- **_Password_** – The password for your remote server if you select Password as your authorization method
- **_Private key_** – Your private key for connecting to the remote server if you select Private key as your authorization method

<p><img src="/images/dashboard/connections/create-connection-2.png" alt="Create connection modal" class="width-60"/></p>

**Note**: You have to create at least one container to create a new connection. Don't know how to create a container? Find out [here](/dashboard/containers/create-new-container).