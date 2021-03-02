# Split-Audio-By-TextGrid  
Env:  
python 3.7  
Window10,x64  
#Split Audio Based on Slient And Sounding

1,Git clone or copy code from this  
2,download ffmpeg from https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z  
3,copy ffmpeg bin file to your project top-level  
4,set Path_dir ='your project dir'  

中文说明：  
运行环境：  
python3.7  
window10 x64   
#基于静音和有声音进行分割操作  
1,拷贝代码到你的python文件  
2，下载ffmpeg压缩包，如果下载比较慢，可以使用迅雷下载  
3，拷贝ffmpeg的bin目录文件，到你的python项目所有目录  
4，运行之前，设置拷贝的代码Path_Dir作为你项目目录  

。TextGrid格式文件获取方式
1，下载Praat语音软件  
@https://github.com/praat/praat  
2，Open-ReadFromFile (支持MP3和Wav等音频格式)  
3，选中音频 点击Annotate-TextGrid(selience)  
4，设置属性，参考属性  
textGrid setting :  
Minimum pitch(HZ) 20  
Mininum silent interval duration 1  
Minimum sounding interval duration 0.1  
  
5，点击Edit&View Ctrl+s 保存文件  



