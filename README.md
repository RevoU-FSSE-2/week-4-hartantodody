
# Introduction

Howdy! I am Dody, a Full Stack Software Engineering Student at RevoU Batch June 2023. Currently I am focusing on learning Web Development using HTML, CSS, and JavaScript.

This Repository is focusing on my Portofolio page which is actually currently still in development, but if you want to look at projects portofolio Click Here to go to the site!


## 🚀 About Me
I'm a (on a way to be a) full stack developer, and aspiring to be one. I was graduated from Institut Teknologi Sepuluh Nopember Surabaya in 2018, and majoring in Information System specialized in Decision Support System.

Right now i am working fulltime as a Loan Administration Staff in a Bank. I realized my interest in Technology especially in Computer Science isn't fading, and believe many opportunities still available in this industry, that's why i tighten my belt and joined RevoU as one of the Full Stack Software Engineering Student. 

## 🌐 My Site Projects
This is a few of many projects that i have created :
- [Dody's Portofolio](https://dodyhartanto.site/) *(the site i used as an example in this guide)*
- [Gunner Gang](https://gunnergang.netlify.app/)

## 📖 Add Custom Domain Guide
In this section, i will guide you to create a custom domain using Niagahoster and Cloudflare from Netlify that linked with your GitHub account, but before that there is something that you need first.
You need to prepare :
- GitHub Account 
- GitHub Repository (Website Project that is ready to deploy)
- Some money (LOL)
- Patience 

### 1. Sign up on Netlify
1. Go to [Netlify](https://www.netlify.com/).
2. Click on the **Sign up** button on the top right corner of the page. *(If you already have netlify account, skip step 2-4)*
![Step 1.2](/readme-img/Screenshot%202023-07-07%20224715.png)
3. Click on the **Sign up with GitHub** button.\
![Step 1.3](/readme-img/Screenshot%202023-07-07%20225112.png)
4. Type your email and password for your registered GitHub Account. And then click **Sign In**.\
![Step 1.4](/readme-img/Screenshot%202023-07-07%20225906.png)
5. In your dashboard menu, look on the left sidebar menu and select **Sites**.
6. You will see all the sites that you have been deployed. Click **Add new site** on the top right deploys list and select **import an existing project**.\
![Step 1.6](/readme-img/Screenshot%202023-07-07%20230428.png)
7. On the Connect to Git Provider menu select GitHub as your provider.
![Step 1.7](/readme-img/Screenshot%202023-07-07%20230657.png)
8. After that you will be checked and authorized by the site and then you need to pick the repository you want to deploy.
![Step 1.8](/readme-img/Screenshot%202023-07-07%20230947.png)
9. Set the Owner and Branch to deploy as you like. 
![Step 1.9.1](/readme-img/Screenshot%202023-07-07%20231322.png)
After you finish setting it up, scroll down find blue button with **Deploy Site** click it, and you almost done!
![Step 1.9.2](/Screenshot%202023-07-07%20231335.png)
10. Wait until Netlify finish deploying your website.
![Step 1.10](/readme-img/Screenshot%202023-07-07%20232040.png)
    1. Meanwhile, you can change your site domain name by clicking the **Domain setting** button. On the right side of your random domain you can see **Options** menu, click it and select **Edit site name**.
    ![Step 1.10.1](/readme-img/Screenshot%202023-07-07%20232122.png)
    2. Type your desired domain name, click **Save** to save the domain name.
    ![Step 1.10.2](/readme-img/Screenshot%202023-07-07%20232228.png)

And there you go! Now you have your own website with your desired name. In the next section we will buy a custom domain in Niagahoster and then making it secure with Cloudflare.

### 2. Buy a Custom Domain in Niagahoster
1. Go to [Niagahoster](https://www.niagahoster.co.id/).
2. Search your own desired custom domain name for your own website in the search bar in the middle. And then click **Cek Sekarang** for it availability.
![Step 2.1](/readme-img/1.PNG)
3. It will move us into a new page with the result like in the picture below. Choose the one that you want, and then click **Pilih** to choose it.
![Step 2.2](/readme-img/2.PNG)
4. You will see the checkout page, click **Lanjutkan** if you agree and accept with the bill.
![Step 2.4](/readme-img/3.PNG)
5. In this checkout menu you need to select the payment method that suitable for you. *(different payment method leads to different price)*
![Step 2.5](/readme-img/4.PNG)
Click **Checkout Sekarang** to pay, and do the payment as the insctruction said.
6. After your payment successfull, wait for a few minutes and your custom domain should be active like shown in the picture below.
![Step 2.6](/readme-img/5.png)

### 3. Setting Up Custom Domain with Cloudflare
1. Go to [Cloudflare](https://dash.cloudflare.com/).
2. Log in if you already have an account. Sign Up if you don't have one yet. *(Skip step 2-4 if you already have an account)*
![Step 3.1](/readme-img/6.PNG)
3. Sign up with your preferred email address and create password as the requierements.
![Step 3.2](/readme-img/7.PNG)
4. After your registration is successfull, you will welcomed by this page.
![Step 3.3](/readme-img/8.PNG)
5. On step 4, you will find a plus logo with **Add site** text button on the top right navigation bar, click it!
6. Add your custom domain that you have bought from Niagahoster.
![Step 3.4](/readme-img/11.png)
7. Choose the Free plan on the bottom.
![Step 3.5](/readme-img/12.png)
8. Click the blue button **Continue** in this page.
![Step 3.6](/readme-img/13.png)
9. In the picture below, look at the step 4, and then copy two of the Cloudflare's nameservers.
![Step 3.7](/readme-img/14.png)
10. Open your Niagahoster account, go to member section, and then click **Kelola Layanan**.
![Step 3.8](/readme-img/15.png)
11. In this page, click on Ubah Nameserver.
![Step 3.9](/readme-img/16.png)
    Paste the Cloudflare's Nameserver that you have copied before and then click Simpan. 
![Step 3.10](/readme-img/17.png)
12. Go Back to Cloudflare, add Type, Name, and Target like the picture that shown below. (add root and www CNAME)
![Step 3.11](/readme-img/19.png)
13. Now open your Netlify account, go to Domain Setting (the one that you changed to your custom domain), and click Add Domain.
![Step 3.12](/readme-img/20.png)
14. Add your custom domain that you have bought from Niagahoster.
![Step 3.13](/readme-img/21.png)
15. Voila! Your site will be hosted from Netlify and using the custom domain that you have bought from Niagahoster.
![Step 3.14](/readme-img/22.png)

And that's it, now you have a website with a custom domain name that linked and protected by Cloudflare.