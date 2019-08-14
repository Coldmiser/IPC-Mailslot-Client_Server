# IPC-Mailslot-Client_Server
IPC-Mailslot Client/Server Example in C#

<h2>Using a Mailslot for IPC</h2>

<blockquote cite="https://docs.microsoft.com/en-us/windows/win32/ipc/interprocess-communications#using-a-mailslot-for-ipc">
<p>Mailslots provide one-way communication. Any process that creates a mailslot is a mailslot server. Other processes, called mailslot clients, send messages to the mailslot server by writing a message to its mailslot. Incoming messages are always appended to the mailslot. The mailslot saves the messages until the mailslot server has read them. A process can be both a mailslot server and a mailslot client, so two-way communication is possible using multiple mailslots.</p>

<p>A mailslot client can send a message to a mailslot on its local computer, to a mailslot on another computer, or to all mailslots with the same name on all computers in a specified network domain. Messages broadcast to all mailslots on a domain can be no longer than 400 bytes, whereas messages sent to a single mailslot are limited only by the maximum message size specified by the mailslot server when it created the mailslot.</p>

<p>Key Point: Mailslots offer an easy way for applications to send and receive short messages. They also provide the ability to broadcast messages across all computers in a network domain. For more information, see Mailslots.</p>
</blockquote>

<p>
  <i><b>IPC Mailslot Example copied from:</b></i><br>
  https://code.msdn.microsoft.com/windowsapps/CSMailslotServer-1ca18b47/sourcecode?fileId=21681&pathId=105306450
</p>
<p>
  <i><b>Documentation from:</b></i><br>
  https://docs.microsoft.com/en-us/windows/win32/ipc/interprocess-communications#using-a-mailslot-for-ipc
</p>
