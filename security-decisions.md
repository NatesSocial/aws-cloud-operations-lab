## Network Security Decisions

- SSH is restricted to my current public IP to reduce unauthorized access.
- HTTP is publicly accessible because the server hosts a demonstration website.
- The server is deployed in a dedicated VPC and subnet.
- A custom route table explicitly controls internet routing.
