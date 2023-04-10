## Getting Started

Node version : 16.20.0  
NextJs version : 11.0.1  
React version : 17.0.2  

sudo npm install  
sudo npm install -g serverless@2.72.2  

To run the development server on local:  
  
```bash  
npm run dev  
# or  
yarn dev  
# or  
pnpm dev  
```  
  
Set your aws crendentials:  
```bash    
aws configure   
AWS Access Key ID [*************xxxx]: <Your AWS Access Key ID>   
AWS Secret Access Key [**************xxxx]:   
<Your AWS Secret Access Key>   
Default region name: [us-east-2]: us-east-2   
Default output format [None]: json  
 ```   
  
  
# To deploy on production : serverless  
```bash  
demo:   
    appUrl:         https://d14ez727nv5i3j.cloudfront.net  
    bucketName:     kcz5psg-8lw281y  
    distributionId: E12EMW8XEGS2910  
  ```  
The above crendentials won't work for you, however when you run serverless command a similar key/value paire will be genaretd, and you can use appUrl as your host to check if you deployment works.  
  
  
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.  

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.  
  
[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.  
  
The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.  

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.  
  
## Learn More  
  
To learn more about Next.js, take a look at the following resources:  
  
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.  
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.  
  
You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!  
  
## Deploy on Vercel  
  
The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.  
  
Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.  
  
    
  
Documentation - https://www.serverless.com/plugins/serverless-nextjs-plugin  
  