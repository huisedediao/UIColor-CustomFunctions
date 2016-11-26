# UIColor-CustomFunctions
UIColor和16进制互转，UIColor转RGBA

<br/>
###示例代码：
<br/>
<pre>
    UIColor *color=[[UIColor colorWithHex:@"#2099f4"] colorWithAlphaComponent:0.6];
    self.view.backgroundColor=color;

    NSArray *arrR=[UIColor RGBAComponentsFromColor:color];
    
    for (NSString *tempStr in arrR)
    {
        NSLog(@"%@\r",tempStr);
    }
    
    NSString *hexStr=[UIColor changeUIColorToRGB:color];
    
    NSLog(@"%@\r",hexStr);
</pre>

<br/><br/>
###运行结果：
![image](https://github.com/huisedediao/UIColor-CustomFunctions/raw/master/show.png)