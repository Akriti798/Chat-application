# Chat-application
Developer- Akriti
<br>
• Description: Built a real-time messaging application with efficient user management, al-
lowing users to send messages, view online status, and join groups.
• Tools Used: C++, Graphs, Queues, and Multithreading for handling concurrent messages.
• Key Features: Implemented message queues for real-time message handling, graph-based
network mapping for friends and groups, and optimized caching algorithms.
<br>
Key Features:
User Management:

Adding users and tracking their online/offline status.
Graph-based Network Mapping:

Tracks friendships or group relationships using an adjacency list (unordered_map<string, set<string>>).
Real-Time Messaging:

Uses threads for sending and receiving messages, allowing concurrent operations.
Message queues (unordered_map<string, queue<string>>) are used to handle asynchronous communication.
Concurrency:

Mutex locks (std::mutex) ensure thread safety when accessing shared resources.
Condition variables (std::condition_variable) notify threads of incoming messages.
Improvements and Scalability:
Group Chats:
Extend friendGraph to include groups as nodes.
Persistent Storage:
Save messages and user data to a database for long-term storage.
Optimized Caching:
Use techniques like LRU (Least Recently Used) caching for active user message queues.
