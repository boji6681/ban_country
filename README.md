# Linux VPS一键屏蔽指定国家所有的IP访问
本脚本适用于`CentOS`、`Debian`、`Ubuntu`等常用系统。

# 使用

``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/boji6681/ban_country/master/ban_country.sh && chmod +x ban_country.sh && bash ban_country.sh
```

# 演示
### 封禁ip
![image](https://github.com/boji6681/ban_country/assets/157291263/c4766c3f-df6a-4e92-a3e6-f06d466f5186)


### 查看封禁列表
![image](https://github.com/boji6681/ban_country/assets/157291263/9e20a9c4-f6d1-4d4c-b529-edbc89e1dcfa)

### 解封IP
![image](https://github.com/boji6681/ban_country/assets/157291263/a3ec32c2-cb10-47cc-a541-cc058e29a14d)




# 总结

一键屏蔽可以有效帮我们暂时防止一些`CC`攻击等，或者你不想让哪国的人进入博客也可以用，注意屏蔽`cn`的时候需谨慎，不然你`SSH`就上不去了。


封禁`ip`时会要求你输入国家代码，代码查看：[点击进入][1]。记住所需输入的参数均为小写字母。比如`JAPAN (JP)`，我们就使用`jp`这个参数。


  [1]: http://www.ipdeny.com/ipblocks
