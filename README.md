# docker-learning
# To push code to docker hub

1. Build the image by
   docker build -t image_name .
2. Tagging the pushing image
   docker tag image_name docker_user_name/image_name:tag_name
3. Push the image
   docker push docker_user_name/image_name:tag_name
