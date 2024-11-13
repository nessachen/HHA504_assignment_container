# HHA504_assignment_container

## GCP Cloud Run
![config-details](https://github.com/user-attachments/assets/bea16234-6e50-43d2-9bab-4ac0a23fd7bc)
![config-details](https://github.com/user-attachments/assets/6d7f78dd-c9d4-4aca-b275-e7b275051165)
![config-details](https://github.com/user-attachments/assets/4d416d82-2802-4160-b885-9c84f8be5398)
![config-details](https://github.com/user-attachments/assets/7568638d-da79-4780-ac3a-9bd45186e2fc)
![config-details](https://github.com/user-attachments/assets/0184c691-7318-461b-b4db-487ea4bc008c)
![flask-deloyed](https://github.com/user-attachments/assets/9713d27d-f2d4-4c77-afa6-171921e2e098)
![gcp-link-view](https://github.com/user-attachments/assets/53ac89f3-3b4f-4470-9fd7-dd2500a17573)

# Reflection
I started by going to GCP and navigating to Cloud Run. For the configurations, I entered the Docker container image URL and gave a name for the Cloud Run service. Under authentication, I made sure to select the option to allow all unauthenticated invocations for the assignment. In the containers section, I entered the port used for the assignment, which was 5000. Next, for the purpose of the assignment, I changed the maximum number of instances from 100 to 3. Then, I pressed Create to deploy the container application. When clicking into the deployed Cloud Run service, I was able to click on the assigned URL to access the flask. 

In my opinion, the most challenging aspect of the assignment was not deploying the containerized application to GCP Cloud Run, but rather developing the HTML file to make the landing page unique and colorful. My approach towards making the flask possess an interactive portion was to create a button that returns a message of `Hello World ☺`.
