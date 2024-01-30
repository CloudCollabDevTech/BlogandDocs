---
date: 2024-01-30
authors: [rishabsharma]
description: >
  This blog article talks about LC NC or UDP - Powered by HCL Volt MX - Primer Series 3 of N. Focus on HCL Leap
categories:
  - VoltMX
comments: true
---

# **UDP (Low-Code No-Code) - Powered by HCL Volt MX - Primer Series 3 / N**

## **Introduction to HCL Leap - No Code**

![Introduction to HCL Leap](https://media.licdn.com/dms/image/D4D12AQGEXF3fQ-ABIA/article-cover_image-shrink_600_2000/0/1706578144348?e=1712188800&v=beta&t=33_UTzQtht98FMagrl1MaYdcXRW-N3RqPe2XRu8KxsM){: style="height:10%;width:40%"}

As explained in the [**previous article**](https://blog.cloudcollabdevtech.com/blog/2024/01/20/low-code-no-code-or-udp-powered-by-hcl-volt-mx---primer-series-2--n.html)- we explored the basic building blocks of HCL Volt MX.

We explained the basic building blocks of HCL Volt MX. In this article we delve and understand **HCL Leap** in a more better manner.

HCL Leap is an agile, easy-to-use tool that allows users to be in control of creating and deploying customer engagement applications and forms, and transforming business processes to achieve greater efficiency. It is the best no-code/low-code platform for creating data capture and process automation web apps on the market.

Think of HCL Leap as a web-based design tool for creating forms, surveys, workflow applications and complex web applications.

<!-- more -->

## **HCL Leap Features**

Before we deep dive into architecture and other aspects it would be worth while to take a look at all the features of HCL Leap.

- **Cloud Style Deployment** - Deploy a single software instance for all your users. Apps and data are secure and only accessible by those who created them and any others who they elect to have access. All use of the software is through your browser or mobile device. You can deploy On-Premises or Cloud Native. You can install or deploy on Managed Kubernetes Environment (MKE) using Helm.
- **Simple Workflow** - Speed the approval process with flexible, role-based workflow and access control. You can automatically generate email notifications, invoke services at workflow steps and provide a dynamic experience based on rules.
- **Adaptive Behaviour** - Applications you create can run on mobile devices and all the popular desktop browsers. Forms will adapt how they render to take advantage of the devices they are being used on.
- **Everything you need** - Design apps and make changes to existing apps in your browser. Deploy them and send out the url. No need to worry about the database and reports and charts as these are all automatically generated.
- **Flexible Integration** - Integrate data from existing systems to pre-populate fields and feed back-end systems with information you collect. The software’s service architecture lets you define connections with just about any connection.
- **Extensible** - Apps can be quickly customized using standard web development skills. Styles can be modified through CSS, functions added as HTML fragments and JavaScript can be used with the software’s comprehensive API and events. So new skills to be acquired. If you are a web developer no additional skills need to be acquired.

## HCL Leap - Terminology

Using HCL Leap allows us to achieve 3 main objectives / activities:

- **Building Forms**
- **Publishing Applications**
- **Reviewing Submissions**

HCL Leap will generate an output which is called either a **Form** or an **Application**.

**Forms** can be single page or a collections of pages which users will interact with.

When you combine a Form with workflow, presentation logic and other elements it becomes an **Application**. **Application** will gather the submitted input and store the same in the designated database.

HCL Leap is also available as **HCL Domino Leap**. These are separate products but share much of the same code base.

**HCL Leap** is based on **IBM WebSphere, DB2** primarily J2EE based whereas **HCL Domino Leap** runs on the **HCL Domino** platform.

[**Link for HCL Domino Leap**](https://www.hcl-software.com/domino/offerings/domino-leap)

## HCL Leap - Architecture

HCL Leap used to known in its earlier avatar as IBM Forms Experience Builder or FEB as we used to called it back then.

HCL Leap is now with HCL Software and we have added a huge number of features, functionality and also integrated the same with our **HCL Volt MX** solution offering completing and complimenting our Unified Development Platform (UDP) capability.

![HCL Leap Architecture](https://media.licdn.com/dms/image/D4D12AQGKGEf-ZN9whQ/article-inline_image-shrink_1000_1488/0/1706578334646?e=1712188800&v=beta&t=rcD87ApO1wehgE09-QoT2BZzz83Enby_08BUZnwSGx8){: style="height:400px;width:720px"}

The components perform the following functions:

- **HCL Leap**: The environment in which you create, deploy and launch applications.
- **IBM HTTP Server** : A standard component of WebSphere® Application Server that interacts with the application server.
- **HCL Leap Database**: The Leap database which contains all applications and data that exist within the Leap environment.

## Closing and Followup

Self Learning Courses for HCL Leap - [**HCL Software University Link**
](https://hclsoftwareu.hcltechsw.com/hcl-leap)

HCL Leap Sandbox - [**Try Leap Today without any installation**](https://leap.hcl-software.com/apps/anon/org/app/3b1d1808-58b2-4364-8d0d-a3bd7238312f/launch/index.html?form=F_Form1&referrer=www.hcl-software.com)

This is the third article on this topic. Next Article we shall dive a little more into HCL Leap. Look out for another one next week. Till then happy reading and reach out to me if you would want more information..

[**See how HCL VoltMX is leading the way with Unified Development Platform and unleashing innovation.**](https://www.hcltechsw.com/volt-mx)
