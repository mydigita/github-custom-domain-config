# github-custom-domain-config
Full guideline for using custom domain to any github repository. 

## Step 1
Open your repositoy and click on Settings

![Repo](/images/open-repo.jpg)


## Step 2

Under the Github Pages -> Source, click on `None`, then select `master` or another branch, then `Save` it

![Select Page Branch](/images/select-page-branch.jpg)

This will publish your project with github-pages via selected branch. So, your site is live now at https://username.github.io/projectname. Now we will set custom domain to our github project. But before that we will edit our main domain DNS configuration. 

## Step 3

Add / point the following IP addresses to your custom domain in DNS zone with `A` record

* 185.199.108.153
* 185.199.109.153
* 185.199.110.153
* 185.199.111.153

Open DNS zone 
![dns-zone](/images/dns-zone.jpg)

Then add the ips
![add-github-ips](/images/add-github-ips.jpg)



## Step 4 

Come back to your repository Settings-> Github Pages, then put your domain name to this field and click on `Save`

![Put your domain name](/images/put-domain-name.jpg)


## Step 5 (fix https issue and review)

After the step 4, your github page will be published with your custom domain name. When you'll visit github project link like [https://tradecoder.github.io/github-custom-domain-config ](https://tradecoder.github.io/github-custom-domain-config) and when you'll visit your custom domain like [https://tradecoder.com](https://tradecoder.com), for both the cases it will load with your custom domain name. It may take few minutes to get effective. 

And if you find in the section of Github Pages that https is not active, it may take upto 24 hours to be active. If not, you may have to remove and add the domain in the github page again. 
![force-https](/images/force-https.jpg)

