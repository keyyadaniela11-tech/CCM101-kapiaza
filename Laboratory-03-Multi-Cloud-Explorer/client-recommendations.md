## Client Recommendations

### Client A — Startup Company

For a startup with a limited budget but plans for rapid growth, AWS is the strongest fit because of its pay-as-you-go pricing and elastic scaling, so the client only pays for what it uses while it is small, then scales up seamlessly as the user base grows. AWS also has the largest startup support ecosystem (e.g., AWS Activate credits), which helps offset early costs. Recommended services: Amazon EC2 for flexible, scalable compute; Amazon S3 for affordable and durable storage of app data and media; and AWS Lambda for serverless functions that avoid paying for idle servers.

### Client B — University

Since the university already relies on Windows Server, Microsoft 365, and Active Directory, Microsoft Azure is the clear recommendation, as it integrates directly with those existing systems and minimizes the need to rebuild identity and access management from scratch. This significantly reduces migration effort and training time for IT staff already familiar with Microsoft tools. Recommended services: Azure Active Directory (Entra ID) to extend the university's existing identity system; Azure Virtual Machines to host servers that are moved to the cloud; and Azure Blob Storage for storing files and backups.

### Client C — AI Research Company

For a company developing AI and machine learning applications that need high-performance computing, Google Cloud Platform is the best fit, given its strong AI/ML toolset and origins as the creator of TensorFlow. GCP's infrastructure is specifically optimized for large-scale data processing and model training, which is exactly what this client needs. Recommended services: Compute Engine with GPU/TPU-enabled instances for training models; BigQuery for fast large-scale data analysis; and Google Kubernetes Engine (GKE) to deploy and scale AI applications in containers.

### Client D — Global E-Commerce Company

For a multinational e-commerce company that needs highly available infrastructure with automatic scaling, AWS is the recommended platform because of its extensive global infrastructure and mature auto-scaling and content-delivery tools. This ensures customers around the world get fast, reliable access to the site even during high-traffic events like sales. Recommended services: Amazon CloudFront for fast global content delivery; EC2 Auto Scaling to automatically handle traffic spikes; and Amazon Route 53 for reliable, low-latency global DNS routing.

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|:---:|:---:|:---|
| Startup Company | AWS | Pay-as-you-go pricing and elastic scaling support fast growth without large upfront cost. |
| Enterprise Organization | AWS | Most mature global infrastructure and widest range of compliance certifications for large-scale operations. |
| Microsoft Environment | Azure | Native integration with Windows Server, Active Directory, and Microsoft 365 reduces migration friction. |
| AI / Machine Learning | GCP | Purpose-built AI/ML tooling (e.g., BigQuery, Vertex AI) and GPU/TPU access for high-performance training. |
| Kubernetes Deployment | GCP | Google created Kubernetes, so GKE offers the most mature, tightly integrated container orchestration. |
| Global Web Application | AWS | Extensive global edge network (CloudFront) and auto-scaling infrastructure for consistent worldwide performance. |
