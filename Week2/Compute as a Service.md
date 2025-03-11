### **Understanding Servers**

*   A **server** is essential for hosting applications, handling **HTTP requests**, and sending responses.
    
*   Servers provide **CPU, memory, and networking** capacity to process user requests.
    
*   **Common HTTP servers**:
    
    *   **Windows-based**: Internet Information Services (IIS)
        
    *   **Linux-based**: Apache HTTP Web Server, Nginx, Apache Tomcat
        
*   To run an **HTTP server on AWS**, you need a compute service from the AWS Management Console.
    

### **Choosing the Right Compute Option**

AWS provides **three types of compute options**:

1.  **Virtual Machines (VMs)**
    
    *   Emulate a physical server.
        
    *   Allow installation of an **HTTP server** for running applications.
        
    *   Require a **hypervisor** to manage resources.
        
    *   AWS service: **Amazon Elastic Compute Cloud (Amazon EC2)**.
        
    *   AWS manages the **host machines, hypervisor, and guest OS**.
        
2.  **Container Services**
    
    *   Use **containerization** to package applications and dependencies.
        
    *   More efficient than VMs but require knowledge of container management.
        
3.  **Serverless Compute**
    
    *   Runs applications without managing servers.
        
    *   AWS automatically handles scaling and resource allocation.
        
    *   Example: **AWS Lambda**.
        

### **Key Takeaways**

*   **Amazon EC2** is the foundation of AWS compute services.
    
*   AWS manages underlying infrastructure, simplifying deployment.
    
*   Understanding **EC2 and virtualization** helps in learning **container services and serverless compute**.
