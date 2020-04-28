[![捐赠雨苁](https://xss001.oss-cn-beijing.aliyuncs.com/shubiao/wx.webp "打赏雨苁")](https://www.ddosi.com)
  
  
[![](https://badgen.net/badge/GoIndex/V1.0.6/008000?icon=github)](https://www.ddosi.com)
[![](https://badgen.net/badge/www.ddosi.com/w.ddosi.workers.dev/blue?icon=github)](https://w.ddosi.workers.dev/)
--------------
Google Drive Directory Index  
Combining the power of [Cloudflare Workers](https://workers.cloudflare.com/) and [Google Drive](https://www.google.com/drive/) will allow you to index you files on the browser on Cloudflare Workers.    

`index.js` is the content of the Workers script.  

## Demo  
material: [https://w.ddosi.workers.dev/](https://w.ddosi.workers.dev/)  
classic: [https://www.ddosi.com/](https://www.ddosi.com/)  

## Deployment  
1.Install `rclone` software locally  
2.Follow [https://rclone.org/drive/]( https://rclone.org/drive/) bind a drive  
3.Execute the command`rclone config file` to find the file `rclone.conf` path  
4.Open `rclone.conf`,find the configuration `root_folder_id` and `refresh_token`  
5.Download index.js in https://github.com/donwa/goindex and fill in root and refresh_token  
6.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)

## Quick Deployment  
1.Open https://installen.gd.workers.dev/  
2.Auth and get the code  
3.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)  



## About  
Cloudflare Workers allow you to write JavaScript which runs on all of Cloudflare's 150+ global data centers.  
