# DragonTrail H5活动管理平台

##模块
    活动、活动时间、活动奖品、活动积分、用户、第三方用户


## 活动创建
    1、后台创建活动，名称唯一
    2、点击活动进入管理，创建活动时间，活动必须存在至少一个时间
    3、在resource/views/activity下创建同名目录，至少存在两个文件:
        index.blade.php  -- 活动主页
        pc.balde.php     -- pc端展示页
        mobile.blade.php -- 手机端展示页面（不存在时调用pc端）
    语法为html语法
    4、在public/static/activity创建同名目录，此目录为静态资源目录

## 前端API
    1、活动
    2、用户