# NSA Challenge -TASK1


# Objective: identify the suspicios artifact inside an ext2 filesystem image and provide its SHA-1 hash.


# step1 : file image.ext2   // identified the file is an filesystem image.

#step 2: sudo mkdir /mnt/TASK1    // create a moun point.
#	sudo mount -o loop,ro image.ext2 /mnt/TASK1  


#step 3: sudo cat /mnt/TASK1/root/.bash_history //analysis the filesystem


#step 4:/etc/secfixes.d/wonaevczsx // Identify the suspicious artifact.


#step 5: sudo sha1sum /mnt/TASK1//etc/secfixes.d/wonaevczsx //Calculate SHA-1.


#### SHA-1 :103b7120eb9d8a271e2fd647b2b2162a3af152ec  /mnt/TASK1//etc/secfixes.d/wonaevczsx

   
