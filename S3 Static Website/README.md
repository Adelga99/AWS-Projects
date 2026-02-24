<h1>This project was hosting a static website in Amazon S3 and routing traffic through Cloudflare DNS</h1>
<h2>Configuring the S3 bucket for static hosting and getting my HTML file uploaded was easy, but I ran into a bit of a road block when it came to the Cloudlfare side of things.</h2>


![alt text](https://github.com/Adelga99/AWS-Projects/blob/main/S3%20Static%20Website/images/static%20website%20config.png)


<p>Because AWS doesn't trust CloudFlare as a CA, I had to set up a page rule under my domain to use Flex SSL so that I could route traffic through CF</p>
