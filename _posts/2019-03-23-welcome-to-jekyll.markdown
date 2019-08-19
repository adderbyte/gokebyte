---
layout: post
title:  "Content Based Image Retrieval : Performance and Similarity Metric Evaluation"
date:   2019-07-23 21:03:36 +0530
categories: ResNet Similarity-measure deep-neural-net
---
Here is the scenario: Given a query image retrieve similar images from the database ? 

-----------

	Summary

----------


Check out the full code implementation  on the Git repository [Content-Based-Image-Retrieval][cbir]. 


-----------

	Detailed Explanation of Approach
	
----------

Assume you have an image of an object and you don't know what name it is called, or what characteristics it has. Then, you might want to do an image search on Yandex, Google or Baidu to help retireve similar objects to your query objects. Once retrieved, you could know everything you want about your query image based on retrieved similar images. 

Thus knowing about the query object is dependent on the performance and accuracy of the retrieval system.

This post  is an attempt to develop a mini image retrieval system. This has importent use in medicine, industrial automation and other domains.

To be continued ...

<!--
```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```
-->


[cbir]: https://github.com/adderbyte/content_based_image_retrieval

