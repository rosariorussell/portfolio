---
title: "Learning Google Cloud"
date: 2019-06-26
featured: false
description: "Google cloud is so much better than AWS!"
image: "/img/blog/gcp.jpg"
---

After completing the bootcamp last year, I immediately began learning. I heard that Google Cloud and Microsoft Azure were relatively new to the cloud infrastrucutre space and decided to go with the gold standard, AWS. Trying to navigate through AWS for the first time is like jumping into airplane cockpit for the first time. There was just too much stuff to comprehend all at once. So I took a course on Udemy which was training for the certification. I completed the course and began working with the <a href="https://serverless.com/">Serverless framework</a>. It was my first glimpse into "infrastructure as code" and "serverless architecture" and I continued down the rabbit hole of DevOps.

A few months later, a friend suggested I try out Google Cloud due to its simplicity. Despite feeling like I had invested a lot of time learning AWS I decided to see what Google Cloud was all about. I completed a few tutorials and immediately recognized that GCP was much better for my needs. I transferred all of my projects and code over to GCP that same week. 

I found GCP to be better than AWS for several reasons.

1. GCP was intuitive & simple - My favorite feature was the cloud shell which allowed me to run CLI commands directly from the GCP console (not available in AWS). Everything is organized into projects which made security and authentication much easier. With AWS I found myself spending way too much time in the IAM panel. Even the GCP menu was less cluttered compared to AWS.
2. Documentation, walkthroughs, and tutorials - I found fewer quantity resources for GCP, but they were significantly higher quality. <a href="https://www.coursera.org/">Coursera</a> has several specializations created by Google themselves. The best part about these courses were the Labs. They were guided walkthroughs which took me from point 0 to the final product like creating a machine learning model or use Apache spark to split computation between thousands of computers. 
3. Integration with other products - Because I use Google Suite for email and other productivity tools, it works seemlessly with all the other software I am using. I also use Google Domains as my registrar so everything works perfectly together.
4. Better for startups - App development is made easy with App Engine. I found it to be much better than AWS Elastic Beanstalk. You can tell Google's target audience is startups whereas AWS is more geared towards large enterprise. Google's acquisition of <a href="https://firebase.google.com/">Firebase</a>, is a perfect example of that. They also gave me an extra $1k in Google Cloud credits after I applied <a href="https://cloud.google.com/developers/startups/">here</a>.
5. Stackdriver - Their logging service has way more features out of the box than AWS Cloudwatch. With AWS, I felt like I needed to export all logs to a third party service, creating even more unnecessary dependencies.
6. Better Machine Learning and big data products - Tensorflow is backed by Google so would seem like they have the upper hand when it comes to Machine Learning. GCP makes it easy to get into machine learning on their platform. They have public datasets, Cloud Datalab for Jupyter notebooks, GUI AI options, and much more. I really enjoyed the Big Data specialization on Coursera which taught me a recommended architecture for big data and streaming processes. Data is ingested through Pub/Sub, transformed through Dataflow using Apache Beam, stored on BigQuery, and analyzed on Data Studio.
7. Cons? - For me the only potential downside was that the Serverless framework does not work as well with GCP. It is supposed to be platform agnostic but I found it to work much more seamlessly with AWS. So not a really big con...
