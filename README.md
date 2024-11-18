steps taken are outlined below:
we made a new diretory called MarketPeak_Ecommerce
mkdir MarketPeak_Ecommerce
cd MarketPeak_Ecommerce
git init
![Screenshot 2024-11-18 182445](https://github.com/user-attachments/assets/a909131b-1bae-4d9b-bdd4-e98939423f0d)
A sample website template was used for this project. Tooplate resource. Extracted template was downloaded to our created file 
GitHub repository was clone to our AWS EC2 instance authenticating with our SSH
![Screenshot 2024-11-18 182820](https://github.com/user-attachments/assets/49a852a4-ce86-418a-a22e-bcf2ccf23cef)
![Screenshot 2024-11-02 215207](https://github.com/user-attachments/assets/cefe12bd-6bd7-4664-931e-00cc85457755)

![Screenshot 2024-11-02 215231](https://github.com/user-attachments/assets/41b3382b-8cb9-45ef-9167-404b1d58a593)
cloning the gitHub was done with our code line: git clone git@github.com:Momohben/MarketPeak_Ecommerce.git
![Screenshot 2024-11-02 215244](https://github.com/user-attachments/assets/232a1faa-2d9e-4884-8126-8acd012b8151)
application was carried out through the super user
![Screenshot 2024-11-02 215259](https://github.com/user-attachments/assets/32a27e02-b2b6-4d86-bf08-9b349d6ed238)
we used apache2 web server, whihc was installed. default web directory was removed and ore market directory files was copied
![Screenshot 2024-11-02 215316](https://github.com/user-attachments/assets/2f3202ed-8ef6-47bc-aca3-2909881c769d)
we noticed there was a block in traffic, our trouble shooting idea was to stop nginx which was initially running, then start apache 2 and reloaded
![Screenshot 2024-11-02 215336](https://github.com/user-attachments/assets/2eb027cd-6b8d-4ed7-8fe4-b557d86e3462)
our web site template was tested using the public ip: 16.171.96.76
![Screenshot 2024-11-02 215356](https://github.com/user-attachments/assets/47d1545c-d231-437b-bf70-df7b4d302818)


