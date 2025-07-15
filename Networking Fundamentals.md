[
  {
    "questionId": "q0000006",
    "question": "While the Network Layer handles logical addressing, which specific functionality at the Transport Layer ensures the reliable, ordered, and error-checked delivery of data streams between applications?",
    "subQuestion": "",
    "domain": "OSI Layer, Data Communications",
    "difficulty": "intermediate",
    "answers": {
      "a": "Packet routing through best path selection.",
      "b": "Segmentation, sequencing, and acknowledgment mechanisms.",
      "c": "Physical addressing and media access control.",
      "d": "Data encryption and compression."
    },
    "correctAnswer": ["b"],
    "references": ["https://www.geeksforgeeks.org/osi-model-architecture/", "https://www.ibm.com/topics/tcp-ip"]
  },
  {
    "questionId": "q0000007",
    "question": "A network administrator needs to divide a Class C network (e.g., 192.168.1.0) into at least 5 usable subnets. Which of the following subnet masks would achieve this requirement while maximizing the number of hosts per subnet?",
    "subQuestion": "",
    "domain": "Subnetting",
    "difficulty": "intermediate",
    "answers": {
      "a": "255.255.255.192 (/26)",
      "b": "255.255.255.224 (/27)",
      "c": "255.255.255.240 (/28)",
      "d": "255.255.255.128 (/25)"
    },
    "correctAnswer": ["b"],
    "references": ["https://www.networkacademy.io/ccna/ip-addressing/subnetting-class-c"]
  },
  {
    "questionId": "q0000008",
    "question": "Consider a scenario where two geographically separated networks need to communicate securely over the public internet. Which network device, beyond basic routing, would be essential to establish and maintain a secure, encrypted tunnel between them?",
    "subQuestion": "",
    "domain": "Data Communications, Network Security",
    "difficulty": "intermediate",
    "answers": {
      "a": "Switch",
      "b": "Hub",
      "c": "VPN Gateway/Router with VPN capabilities",
      "d": "Repeater"
    },
    "correctAnswer": ["c"],
    "references": ["https://www.cisco.com/c/en/us/products/security/vpn-gateways.html"]
  },
  {
    "questionId": "q0000009",
    "question": "While TCP provides reliable data transfer, what is the key characteristic of UDP that makes it preferable for real-time applications like voice and video conferencing, despite its unreliability?",
    "subQuestion": "",
    "domain": "OSI Layer, Data Communications",
    "difficulty": "intermediate",
    "answers": {
      "a": "It performs extensive error checking and retransmission.",
      "b": "It establishes a connection before data transmission, ensuring session integrity.",
      "c": "Its connectionless and minimal overhead nature allows for faster transmission with lower latency.",
      "d": "It guarantees ordered delivery of packets, preventing jitter."
    },
    "correctAnswer": ["c"],
    "references": ["https://www.geeksforgeeks.org/differences-between-tcp-and-udp/"]
  },
  {
    "questionId": "q0000010",
    "question": "You are given an IP address 172.16.0.0 and need to create a subnet mask that supports approximately 500 hosts per subnet. Which of the following CIDR notations would be the most appropriate?",
    "subQuestion": "",
    "domain": "Subnetting",
    "difficulty": "intermediate",
    "answers": {
      "a": "/22",
      "b": "/23",
      "c": "/24",
      "d": "/25"
    },
    "correctAnswer": ["b"],
    "references": ["https://www.iplocation.net/cidr", "https://www.networkacademy.io/ccna/ip-addressing/how-to-subnet"]
  }
]
