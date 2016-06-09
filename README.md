# LXMSnippets
some snippets to simplify coding

用代码块来简化敲一些重复的代码~参见 [http://nshipster.cn/xcode-snippets/](http://nshipster.cn/xcode-snippets/)

## 使用方法：    
将这些.codesnippet文件copy到~/Library/Developer/Xcode/UserData/CodeSnippets/这个目录下面，重启Xcode就可以了~    
注意要完全退出Xcode才行，Xcode下面有亮点可是不行的~    
想想仅用输入几个字母就能出现一行代码的感觉还真是有点爽歪歪呀~    

## 目前支持:    
在@interface 中    
strong  ->  @property (nonatomic, strong) type name;    
weak  ->  @property (nonatomic, weak) type name;    
copy  ->  @property (nonatomic, copy) type name;    
assign  ->  @property (nonatomic, assign) type name;    
    
integer  ->  @property (nonatomic, assign) NSInteger name;    
float  ->  @property (nonatomic, assign) CGFloat name;    
array  ->  @property (nonatomic, strong) NSArray *name;    
string  ->  @property (nonatomic, copy) NSString *name;    
    
delegate  ->  @property (nonatomic, weak) id<xxxDelegate> delegate;  
    
在@implementation中    
@tableView -> tableView常用的几个dataSource和delegate方法    



# License    
LXMSnippets is provided under the MIT license. See LICENSE file for details.
