# Eduminatti Assignment

This is an Internship Assignment that was supposed to be submitted as a Selection Process.

## Recommendations

After going through a few reports of GT Metrix and others and digging a bit more into the site, I discovered some of these issues, which needs to fixed in order to rank the website and also decrease the load time of the website. Along with the Recommendations.txt, I have also attached the reports if you need more technical analysis. Here are the my recommendations and the same can be found in the recommendations.txt file. 

1. *Properly size images :*   

     Serve images that are appropriately-sized to save cellular data and improve load time. In the Report, It can be clearly seen that site takes most of the time to load images. Seems images are in png and jpg format. Modern Generation image formats like webp and svg can be used to optimize images. Also Delivering Static files via CDN would enhance the speed to a greater extent.
  
2. *Minify CSS :*
  
   Minifying CSS files can reduce network payload sizes. Also Delivering these Static Files over CDN can enhance the speed to a greater extent.

3. *Minify JavaScript :*

   Minifying JavaScript files can reduce payload sizes and script parse time. Firstly, effecient JS code must be written, and then using White Space Remover Tools can help decrease the size of Javascript Files. 

4. *Reduce unused CSS* : 

 
   Reduce unused rules from stylesheets and defer CSS not used for above-the-fold content to decrease bytes consumed by network activity.  Also by removing direct web link for linking css and linking css over a cdn can also enhace the site load speed.

5. *Reduce unused JavaScript :*


   Reduce unused JavaScript and defer loading scripts until they are required to decrease bytes consumed by network activity.  
Efficiently encode images

6. *Optimized images load faster and consume less cellular data :*

  
   Serve images in next-gen formats
Image formats like WebP and AVIF often provide better compression than PNG or JPEG, which means faster downloads and less data consumption.  As in the Report, It can be clearly seen that most of the delay is due to Higher Resolution Images.

7. *Enable text compression :*


   Text-based resources should be served with compression (gzip, deflate or brotli) to minimize total network bytes.  

8.  *Initial server response time was short :*

    Keep the server response time for the main document short because all other requests depend on it.  

9. *Use video formats for animated content :*

   Large GIFs are inefficient for delivering animated content. Consider using MPEG4/WebM videos for animations and PNG/WebP for static images instead of GIF to save network bytes.

10. *Remove duplicate modules in JavaScript bundles :*

    Remove large, duplicate JavaScript modules from bundles to reduce unnecessary bytes consumed by network activity. 

11. *Using Lazy Loader :*

    Instead of serving the HTML only when the page is completely ready. Rather using Lazy Loaders will help increase the User Experience. 

12. *Browser errors were logged to the console :*

    Errors logged to the console indicate unresolved problems. They can come from network request failures and other browser concerns. Some of these errors can be seen in the image.

13. *Keep request counts low and transfer sizes small :*

    To set budgets for the quantity and size of page resources, add a budget.json file.

14. *Image elements do not have explicit width and height :*

    Set an explicit width and height on image elements to reduce layout shifts and improve.

15. *Avoid large layout shifts 2 elements found :*

    These DOM elements contribute most to the CLS (Cumulative Layout Shift) of the page.


## Tools used 
Here are some of the tools I used to analyse the site and get the above insights. More detailed technical reports can be found on these website.
- GT Metrix
- Lighthouse 
- Google Analytics
- Googles PageSpeed Test
- Ping
- Ping DOM
- Web Page Test
- Dotcom Tools.
