---
title: "Overview of when to use REST or SOAP web services"
description: "Overview documentation that compares REST and SOAP web services"
author: "Amson Liu"
doc_type: Overview doc
date: 03/21/2024
---

# Overview of when to use REST or SOAP web services

In this article, you will learn about REST and SOAP web services and consider which scenarios to use which. Both REST and SOAP are popular approaches to the process of implementing APIs, or application programming interfaces.

## What are REST APIs?

REST is an acroynm for Representational State Transfer. REST APIs have the advantage of being flexible. You may choose to transmit data in a varity of formats such as HTML, XML, JSON, and even plain text.

## What are SOAP APIs?

SOAP is an acronym for Simple Object Access Protocol. SOAP APIs have the advantage of being more secure than REST APIs. However, it is less flexible because the data can only be transmitted in the XML format.

## Which one should you use?

In most scenarios, you should use REST APIs when prioritizing flexibility and efficiency. However, it may be appropiate to use SOAP APIs when security and consistency are paramount to the goals of your project.

Here are some common examples to use REST APIs:

1. Developing public APIs
2. Situations involving limited bandwidth or server resources
3. Creating mobile applications

Here are some common examples to use SOAP APIs:

1. Developing private APIs, such as enterprise software
2. Situations involving stateful operations
3. Using non-HTTP transfer protocols such as SMTP

## Next steps

To get a comprehensive overview about REST and SOAP web services, you may consult the following sources.

1. [SOAP vs. REST APIs: The Key Differences Explained for Beginners](https://blog.hubspot.com/website/rest-vs-soap)
2. [What is the Difference Between SOAP and REST?](https://aws.amazon.com/compare/the-difference-between-soap-rest/)
