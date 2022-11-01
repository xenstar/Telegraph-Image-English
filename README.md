
I just translated the Script to English Version. Feel free to fork it! :) 

![image](https://user-images.githubusercontent.com/55502651/199361354-7aa21926-cb97-42a2-bd92-48a6f421c52f.png)

**Preparation**

Step-by-Step Instruction

3 simple steps to deploy this project and have your own Share Screenshot website.

1. Download or fork this repository.

2. Open the Cloudflare Dashboard, enter the Pages management, select Create a project, and if you choose to fork this repository in the first step, select Connect to Git provider; if you chose to download this repository in the first step, select Upload directly.

![image](https://user-images.githubusercontent.com/55502651/199361740-fbcfec74-1c6d-49c6-8705-a53923858429.png)

![image](https://user-images.githubusercontent.com/55502651/199361809-83ba910a-27e1-4183-b19e-50b4c1c96d08.png)

3. Follow the prompts on the page to enter the project name, select the git repository you need to connect to (the first step is to choose fork) or upload the repository file you just downloaded (the first step is to choose download this repository), click deploy site to complete the deployment.

**Features**

1. Unlimited picture storage, you can upload unlimited pictures.

2. There is no need to purchase a server, it is hosted on Cloudflare's network, and it is completely free when the usage does not exceed Cloudflare's free quota.

3. No need to buy a domain name, you can use the free second-level domain name of *.pages.dev provided by Cloudflare Pages, and also supports binding custom domain names.

**Binding Custom Domains**

Inside the custom domain of pages, bind the domain name that exists in cloudflare, the domain name hosted in cloudflare, will automatically modify the dns record.

**Limitations:**

1. Since the image files are actually stored in Telegraph, Telegraph limits the size of uploaded images to a maximum of 5MB

2. Due to the use of Cloudflare's network, the loading speed of images may not be guaranteed in some areas.

3. The free version of Cloudflare Function is limited to 100,000 requests per day (i.e. the total number of uploads or loads of images cannot exceed 100,000), if this is exceeded, you may need to choose to purchase the paid package of Cloudflare Function.

Thanks to

Hostloc @feixiang and @乌拉擦 for the ideas and code
