###docker buildx
    
    docker buildx build --platform linux/arm,linux/arm64,linux/amd64 -t qingfeng2336/spirit --push -f ./Dockerfile .
    
## 映射目录

/resources/video   to download addr


eg 
a2 down
	下载器设置的目录     /resources/video        挂载处理媒体

	随意			       /resources/cover      封面

	随意              /app/db               数据库