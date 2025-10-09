### Cloud Storage Resources
---
> Infrastructure providers also offer their customers storage resources, both storage that is coupled with their computing offerings and independent storage offerings for use in building other cloud architectures.

### Block Storage 
---
>[!note]
>- allocates large volumes of storage for **use by virtual server instance(s).**
>- These volumes are then formatted as **virtual disks by the operating system on those server instances and use as they would a physical drive.**
>- AWS offers a Block storage through **EBS** service 

### Object Storage 
---
>[!note]
>- Provides customers with the ability to **place files in buckets and treat each file as an independent entity** that may be accessed over th**e web or through the provider's API.**
>- Customers don't know of the underlying storage structure like disks or volumes 



>[!important]
>- Block storage is **more expensive the** object storage 
>- In block storage you have a prealloc space that you have to pay for 
>- In Object storage you have to pay only for the storage you use 


### Security considerations about storage 
---
- **set permission properly**  
	- access policies placed on the storage 
	- which files face the web and which do not 
- **consider high availability**
	- use SP replication capabilities or implement your own to accomodate availability requirements 
- **use encryption**
	- apply own encryption or FDE while accessing files 