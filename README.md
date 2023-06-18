# image 2 tar 

Docker Image to `.tar` file Conversion

## Procedure 

- List `docker` images to identify the image you want to convert into a `tar` file. Use the following command to list your images:

```bash
docker images
```

- Once you have identified the image, you can proceed to save it as a `tar` file. Use the following command, replacing `image_name` with the actual name or ID of your image:

```bash
docker save -o image_name.tar image_name
```

- Docker will save the image as a `tar` file in the current directory. You can verify this by listing the files using the `ls` command.

- **For example**

![image](https://github.com/ShubhamKumar89/docker-image-2-tar-file/assets/97805339/da0d146d-bf2a-42bc-b4aa-1d5f4bb26757)
