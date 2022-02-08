# first-S3-bucket
An explanation of the first time I have set up an S3 bucket


This was a fairly basic lab. I created an S3 bucket using the naming convention. The names have to be unique and cannot contain capital letters or underscores. After creating the bucket I uploaded an image file then opened the file using the "Open" button and the image url. The image url brought up an xml screen stating that access to view the image was denied, which means on the public side of the internet there is no way to access the image. I then created a folder and uploaded an image file to the folder. I deleted the folder after that. 

In the next section of the lab I changed the permissions on the bucket to public, allowing anyone to access the image inside of the bucket based on the public URL. To do this I created a policy using the policy generator, giving anyone get-object access.
