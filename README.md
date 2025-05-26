# RemotingClientServer
# .NET Remoting with TCP Channel

This project demonstrates a simple **.NET Remoting architecture** using a **TCP channel** to establish communication between a **server** and a **client** in a distributed system.

---

## 🔧 Features

- Distributed architecture using .NET Remoting
- Communication over **TCP Channel**
- Shared DLL for both client and server (remote object interface)
- Demonstrates:
  - Marshal By Reference
  - Server Activated Object (Singleton/SingleCall)
  - Client Activation support

---

## 🗂️ Project Structure

```

DotNetRemotingDemo/
├── SharedLib/           # DLL used by both client and server
│   └── IRemoteService.cs
├── RemotingServer/      # Hosts the remote object
│   └── Program.cs
├── RemotingClient/      # Consumes the remote object
│   └── Program.cs

```

---

## 🚀 How to Run

1. **Build all projects** in Visual Studio (.NET Framework required)
2. **Start the Server** project:
   - It registers the remote object over TCP
3. **Start the Client** project:
   - It connects to the server and invokes remote methods via TCP

---

## 🔌 Key Concepts Used

- ✅ TCP Channels
- ✅ Marshal By Reference
- ✅ Server-Activated Objects (SAO)
- ✅ Shared interface via DLL

---

## 📝 Requirements

- .NET Framework (4.x)
- Visual Studio (2019 or newer)

---

## 📚 References

- DCOM, RMI, CORBA (conceptual base)
- .NET Remoting (MSDN legacy technology)
```
