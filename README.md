pyvim
=====

my simple vimrc for python  

##Vundle
Use [Vundle.vim](https://github.com/gmarik/Vundle.vim) to manage all the plugin  
So install vundle first:  
  
```bash  
$ git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim  
```  

Then edit your .vimrc file,save it.Run this in vim:  
  
```bash    
:PluginInstall   
```  

##YouCompleteMe  

Use [YouCompleteMe](https://github.com/Valloric/YouCompleteMe),it is more powerful  
than python-mode  

After install plugins,you may see this error:  
  
> ycm_client_support.[so|pyd|dll] and ycm_core.[so|pyd|dll] not detected;  
> you need to compile YCM before using it. Read the docs!  

Please install YouCompeteMe is this way:  
  
1. install python-dev and CMake   
  
```bash  
$ sudo apt-get install python-dev  
$ sudo apt-get install CMake  
```

2. install YouCompleteMe  
  
```bash  
$ cd ~/.vim/bundle/YouCompleteMe  
$ sudo sh install.sh  
```  

###Threre are no best vimrc,but you can make it better for youself!
