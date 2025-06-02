# 🧠 Computer Networks Lab – JEC

This repository contains all lab work done for the **Computer Networks Lab** as per the JEC syllabus. It includes socket programming in C and Python, and GNS3 simulations of Layer 2 & Layer 3 networking.

---

## 📁 Lab Contents

### 🔌 Socket Programming

| Program         | Description                         |
|----------------|-------------------------------------|
| `tcp_server.c`  | TCP Server for simple echo/message  |
| `tcp_client.c`  | TCP Client                          |
| `chat_server.c` | Bidirectional TCP Chat Server       |
| `chat_client.c` | Bidirectional TCP Chat Client       |
| `udp_server.c`  | UDP Server                          |
| `udp_client.c`  | UDP Client                          |

---

## ⚙️ Compilation & Execution

Make sure you are using **GCC** or any standard C compiler.

### TCP Programs

```bash
gcc tcp_server.c -o tcp_server
gcc tcp_client.c -o tcp_client

# Run server first
./tcp_server

# In another terminal
./tcp_client


### TCP chat Program

gcc chat_server.c -o chat_server
gcc chat_client.c -o chat_client

# Run server first
./chat_server

# In another terminal
./chat_client


### Udp Programs
gcc udp_server.c -o udp_server
gcc udp_client.c -o udp_client

# Run server first
./udp_server

# In another terminal
./udp_client

