 /*
22.6.1.bak
*/

{
"wallpaper":"https://picsum.photos/1280/720/?blur=10",

/*
zxy带火箭爬虫
"spider": "https://gitee.com/dongji2/mm/raw/master/bak/sprider_zxy220517.jar",
*/

/*mq带动物爬虫 推送
"spider": "https://gitee.com/dongji2/mm/raw/master/bak/custom_spider_mq220521.txt?download=true;md5;3d7a34c9ce1320bcd60b6b8fcbacd28b",
*/

"spider": "https://gitee.com/dongji2/mm/raw/master/bak/dj-xb-v2.jar",


"sites": [ 


{"key":"csp_77","name":"【默认主页🐞】七七","type":3,"api":"csp_Kunyu77","searchable":1,"quickSearch":1,"filterable":1},


/*自用xp*/
{"key":"csp_xpath_jrskan","name":"【DJ-XP🏀】JRS直播","type":3,"api":"csp_XPath","searchable":0,"quickSearch":0,"filterable":0,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/jrskan.json"},
{"key": "csp_xpath_88kanqiu","name": "【DJ-XP🏀】88看球","type": 3,"api": "csp_XPath","searchable": 0,"quickSearch": 0,"filterable": 0,"ext": "https://gitee.com/dongji2/mm/raw/master/xp/88kaniqiuV2.json"},
{"key": "csp_xpath_虎牙直播","name": "【DJ-XP🎸】虎牙直播","type": 3,"api": "csp_XPath","searchable": 0,"quickSearch": 0,"filterable": 0,"ext": "https://gitee.com/dongji2/mm/raw/master/xp/huya.json"},


{"key":"csp_xpath_lezhutv","name":"【DJ-XP】乐猪TV","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/lezhutv.json"},
{"key":"csp_xpath_saohuo","name":"【DJ-XP】SH电影","type":3,"api":"csp_XPathMac","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/saohuo.json"},
{"key":"csp_xpath_jubaibai","name":"【DJ-XP】剧白白","type":3,"api":"csp_XPathMacFilter","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/jubaibai.json"},

{"key":"csp_xpath_libvio","name":"【DJ-XP】libvio","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/libvio.js"},
{"key":"csp_xpath_zxzj","name":"【DJ-XP】在线之家","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/zxzj.json"},
{"key":"csp_xpath_9eguoyu","name":"【DJ-XP】九亿国语","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/9eguoyu.js"},
{"key":"csp_xpath_31kan","name":"【DJ-XP】31看","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/31kan.js"},
{"key":"csp_xpath_555","name":"【DJ-XP】555电影","type":3,"api":"csp_XPath","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://gitee.com/dongji2/mm/raw/master/xp/555.js"},

{"key": "csp_XPathMacFilter_极品","name": "【DJ-XP】极品影院","type": 3,"api": "csp_XPathMacFilter","searchable": 1,"quickSearch": 1,"filterable": 1,"ext": "https://gitee.com/dongji2/mm/raw/master/xp/pb/07-极品极链.js"},
{"key": "csp_XPathMacFilter_达达龟","name": "【DJ-XP】达达龟","type": 3,"api": "csp_XPathMacFilter","searchable": 1,"quickSearch": 1,"filterable": 1,"ext": "https://gitee.com/dongji2/mm/raw/master/xp/ce/dadagui.json"},

{"key": "csp_biubiu_小强迷","name": "<DJ-XB💖>小强迷","type": 3,"api": "csp_XBiubiu","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://gitee.com/dongji2/bb/raw/master/custom/sj/小强迷.json"},
{"key": "csp_biubiu_lezhutv","name": "<DJ-XB💖>飘花播播","type": 3,"api": "csp_XBiubiu","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://gitee.com/dongji2/bb/raw/master/custom/sj/飘花播播.json"},

{"key": "csp_biubiu_花猫TV","name": "<DJ-XB💖>花猫TV","type": 3,"api": "csp_XBiubiu","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://gitee.com/dongji2/bb/raw/master/custom/01-花猫TV.json"},
{"key": "csp_biubiu_天空影视","name": "<DJ-XB💖>天空影视","type": 3,"api": "csp_XBiubiu","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://gitee.com/dongji2/bb/raw/master/custom/天空影视.txt"},
{"key": "csp_biubiu_影视工厂","name": "<DJ-XB💖>影视工厂","type": 3,"api": "csp_XBiubiu","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://gitee.com/dongji2/bb/raw/master/custom/影视工厂.txt"},
{"key": "csp_biubiu_饭团影院","name": "<DJ-XB💖>饭团影院","type": 3,"api": "csp_XBiubiu","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://gitee.com/dongji2/bb/raw/master/custom/饭团影院.txt"},
{"key": "csp_biubiu_奇粹影院","name": "<DJ-XB💖>奇粹影院","type": 3,"api": "csp_XBiubiu","searchable": 1,"quickSearch": 1,"filterable": 0,"ext": "https://gitee.com/dongji2/bb/raw/master/custom/02-奇粹影院.txt"},


{ "key": "优酷视频(官源)", "name": "优酷视频(官源)", "type": 0, "api": "http://zy.yilans.net:8090/api.php/provide/vod/from/youku/at/xml/", "searchable": 1, "quickSearch": 1, "filterable": 0 }, 
{ "key": "爱奇艺(官源)", "name": "爱奇艺(官源)", "type": 0, "api": "http://zy.yilans.net:8090/api.php/provide/vod/from/qiyi/at/xml/", "searchable": 1, "quickSearch": 1, "filterable": 0 }, 
{ "key": "腾讯视频(官源)", "name": "腾讯视频(官源)", "type": 0, "api": "http://zy.yilans.net:8090/api.php/provide/vod/from/qq/at/xml/", "searchable": 1, "quickSearch": 1, "filterable": 0 }, 
{ "key": "芒果TV(官源)", "name": "芒果TV(官源)", "type": 0, "api": "http://zy.yilans.net:8090/api.php/provide/vod/from/mgtv/at/xml/", "searchable": 1, "quickSearch": 1, "filterable": 0 }, 
{ "key": "搜狐视频(官源)", "name": "搜狐视频(官源)", "type": 0, "api": "http://zy.yilans.net:8090/api.php/provide/vod/from/sohu/at/xml/", "searchable": 1, "quickSearch": 1, "filterable": 0 }, 

{"key":"官方采集","name":"官方采集","type":1,"api":"https://gfzycj.hnmj.vip/api.php/provide/vod/","searchable":1,"quickSearch":1,"filterable":1},
{"key":"会员采集","name":"会员采集","type":1,"api":"http://caiji.nxflv.com/api.php/provide/vod/","searchable":1,"quickSearch":1,"filterable":1},


{"key":"8090资源(含官采)","name":"8090资源网(含官采)","type":0,"api":"http://zy.yilans.net:8090/api.php/provide/vod/at/xml/","searchable":1,"quickSearch":1,"filterable":0},
{"key":"m3u8资源(含官采)","name":"m3u8资源(含官采)","type":1,"api":"http://www.zycaiji.net:7788/api.php/provide/vod/?ac=list","searchable":1,"quickSearch":1,"filterable":0},
{"key":"360官采","name":"360官采","type":1,"api":"http://360.tgzy.cc/api.php/provide/vod/?ac=list","searchable":1,"quickSearch":1,"filterable":0},


{"key":"csp_appysv2_益达影院","name":"益达影院","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://yidayy.top/lehailb_api.php/v1.vod"},
{"key":"csp_appysv2_4K影院啊","name":"4K影院啊","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://1api.4kdytv.com/api.php/v1.vod"},
{"key":"csp_AppYsV2_秒播秒播","name":"秒播秒播","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://mkk.gotka.top/api.php/v1.vod"},
{"key":"csp_appysv2_嗷呜视频","name":"嗷呜视频","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.cx99999.cn/lvdou_api.php/v1.vod"},
{"key":"csp_AppYs_美剧虫啊","name":"美剧虫啊","type":3,"api":"csp_AppYs","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://meijuchong.com/api.php/v1.vod"},
{"key":"csp_AppYsV2_xiaogui_躺平蓝光","name":"躺平蓝光","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://www.lltpys.com/xgapp.php/v1/"},
{"key":"csp_AppYsV2_美剧范啊","name":"美剧范啊","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://ttzmz.net/api.php/v1.vod"},
{"key":"csp_AppYs_琅琊影视","name":"琅琊影视","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://fgyuu.top/lehailb_api.php/v1.vod"},
{"key":"csp_AppYsV2_暖光影视","name":"暖暖影视","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://app.bl210.com/api.php/v1.vod"},
{"key":"csp_AppYsV2_雪人影视","name":"雪人影视","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://qqtvapp.com/xgapp.php/v1/"},
{"key":"csp_appysv2_段友影视","name":"段友影视","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://shangjihuoke.com/api.php/tv.vod"},
{"key":"csp_appysv2_懒猫电影","name":"懒猫电影","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://lanmao.lanmaoymw.cn/api.php/v1.vod"},
{"key":"csp_appysv2_益达影院","name":"益达影院","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://luobu.yss6080.com/mogai_api.php/v1.vod"},


{"key":"csp_AppYsV2_v1_蓝光动漫","name":"蓝光动漫","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"https://v.lvdi.vip/api.php/app/"},
{"key":"csp_AppYsV2_v1_蜗牛动漫","name":"蜗牛视频","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://woniudm.woniu.cyou:20000/mogai_api.php/v1.vod"},
{"key":"csp_AppYsV2_v1_麻子视频","name":"麻子视频","type":3,"api":"csp_AppYsV2","searchable":1,"quickSearch":1,"filterable":1,"ext":"http://aliyun.k8aa.com/mogai_api.php/v1.vod"},

/*mq推送
{"key": "push_agent","name": "推送","type": 3,"api": "csp_Push","searchable": 0,"quickSearch": 0,"filterable": 0}
*/

{"key": "push_agent","name": "推送","type": 3,"api": "csp_PushAgent","searchable": 0,"quickSearch": 0,"filterable": 0}

],


/*
"lives": [{"group": "redirect","channels": [{"name": "redirect","urls": 
["proxy://do=live&type=txt&ext=aHR0cHM6Ly93ZHMuZWNzeHMuY29tLzIyMjcxMi5qcw=="]}]}], 
*/


  /*  以下是电视频道  */

 "lives":[

 {
            "group":"常看频道",
            "channels":[
                {
                    "name":"上海新闻s",
                    "urls":[
"http://219.151.31.38/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/4000000/mnf.m3u8",
"http://219.151.31.38/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/2300000/mnf.m3u8",
"http://219.151.31.37/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/4000000/mnf.m3u8",
"http://219.151.31.37/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/2300000/mnf.m3u8"
                    ]
                },

             {"name":"H_张大仙688","urls":["http://epg.112114.xyz/huya/688"]}

            ]
        },


        {
            "group":"体育频道",
            "channels":[
                {
                    "name":"五星体育",
                    "urls":[
                        "http://shbu.live.bestvcdn.com.cn:8080/live/program/live/ssty/2300000/mnf.m3u8",
                        "http://shbu.live.bestvcdn.com.cn:8080/live/program/live/ssty/4000000/mnf.m3u8",
                        "http://140.207.241.2:8080/live/program/live/ssty/2300000/mnf.m3u8",
                        "http://iptv.tvfix.org/hls/wxtyhd.m3u8"
                    ]
                },
                {
                    "name":"劲爆体育",
                    "urls":[
"http://219.151.31.37/liveplay-kk.rtxapp.com/live/program/live/jbtyhd/4000000/mnf.m3u8",
"http://219.151.31.37/liveplay-kk.rtxapp.com/live/program/live/jbtyhd/2300000/mnf.m3u8",
"http://219.151.31.38/liveplay-kk.rtxapp.com/live/program/live/jbtyhd/4000000/mnf.m3u8",
                        "http://shbu.live.bestvcdn.com.cn:8080/live/program/live/jbtyhd/2300000/mnf.m3u8",
                        "http://shbu.live.bestvcdn.com.cn:8080/live/program/live/jbtyhd/4000000/mnf.m3u8",
                        "http://140.207.241.2:8080/live/program/live/jbtyhd/2300000/mnf.m3u8",
                        "http://140.207.241.2:8080/live/program/live/jbtyhd/4000000/mnf.m3u8"
                    ]
                },
                {
                    "name":"CCTV-5体育",
                    "urls":[
"http://ottrrs.hl.chinamobile.com/PLTV/88888888/224/3221226019/index.m3u8",                       
"http://39.134.67.226/PLTV/88888888/224/3221225818/index.m3u8",
"http://dbiptv.sn.chinamobile.com/PLTV/88888890/224/3221226395/index.m3u8",
"http://111.40.196.9/PLTV/88888888/224/3221225743/index.m3u8",
"http://39.134.115.163:8080/PLTV/88888910/224/3221225633/index.m3u8",
"http://39.135.138.58:18890/PLTV/88888888/224/3221225751/index.m3u8"
                    ]
                },
                {
                    "name":"CCTV-5+体育",
                    "urls":[
                        "http://39.134.65.175/PLTV/88888888/224/3221225507/index.m3u8",
"http://117.148.179.136/PLTV/88888888/224/3221231459/index.m3u8",
                        "http://39.135.138.60:18890/PLTV/88888910/224/3221225649/index.m3u8",
                        "http://39.135.138.60:18890/PLTV/88888910/224/3221225706/index.m3u8",
                        "http://cctvalih5ca.v.myalicdn.com/live/cctv5plus_2/index.m3u8",
                        "http://39.134.115.163:8080/PLTV/88888910/224/3221225649/index.m3u8",
                        "http://39.135.46.246:6610/PLTV/77777777/224/3221225621/index.m3u8?hls",
                        "http://39.135.140.226:6410/PLTV/88888888/224/3221225649/2/index.m3u8?fmt=ts2hls",
                        "http://42.176.185.28:9901/tsfile/live/1004_1.m3u8",
                        "http://39.135.138.60:18890/PLTV/88888910/224/3221225649/index.m3u8"
                    ]
                },

{"name":"纬来体育","urls":["rtmp://59.124.75.150/sat/tv721"]},

                {
                    "name":"JRS直播",
                    "urls":[
"https://d1k4ybyeycgihx.cloudfront.net/hls/TNT/chunks.m3u8",
"https://hlsli.mszgjy.com/live/11s/playlist.m3u8?k=848f28c8c5ca63f596eff87de9b8e647&t=1651708377",
"http://mtw.so/5NosNX",
"http://mtw.so/69X63E",
"http://mtw.so/5FNAQ7"
                    ]
                }
            ]
        },

  {
            "group":"上海频道",
            "channels":[
                {
                    "name":"上海新闻s",
                    "urls":[
"http://219.151.31.38/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/4000000/mnf.m3u8",
"http://219.151.31.38/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/2300000/mnf.m3u8",
"http://219.151.31.37/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/4000000/mnf.m3u8",
"http://219.151.31.37/liveplay-kk.rtxapp.com/live/program/live/xwzhhd/2300000/mnf.m3u8"
                    ]
                },
                {
                    "name":"上海生活",
                    "urls":[
                        "http://183.207.255.188/live/program/live/shsshd/4000000/mnf.m3u8"
                    ]
                },
                {
                    "name":"上海都市",
                    "urls":[
                        "http://183.207.255.188/live/program/live/ylpdhd/4000000/mnf.m3u8"
                    ]
                },
                {
                    "name":"上海影视",
                    "urls":[
                        "http://183.207.255.188/live/program/live/dsjpdhd/4000000/mnf.m3u8"
                    ]
                },
                {
                    "name":"上海外语",
                    "urls":[
                        "http://183.207.255.188/live/program/live/wypdhd/4000000/mnf.m3u8"
                    ]
                },
                {
                    "name":"上海纪实",
                    "urls":[
                        "http://183.207.255.188/live/program/live/jspdhd/4000000/mnf.m3u8"
                    ]
                }
            ]
        },

        {
            "group":"音乐频道",
            "channels":[
                
{"name":"D_点歌台","urls":["http://zzy789.xyz/douyu1.php?id=3870925"]},
{"name":"D_蓝光乐队","urls":["http://zzy789.xyz/douyu1.php?id=9572351"]},
{"name":"D_韩语歌曲","urls":["http://zzy789.xyz/douyu1.php?id=603070"]},
{"name":"D_周杰伦","urls":["http://zzy789.xyz/douyu1.php?id=7537296"]},

{"name":"Q_德云社","urls":[
"http://65537ff319007c0310e1b87d7061588a.v.smtcdns.net/txpcdn.liveplay.egame.qq.com/live/3954_421447299.m3u8"]},
{"name":"Q_德云社","urls":[
"http://65537ff319007c0310e1b87d7061588a.v.smtcdns.net/txpcdn.liveplay.egame.qq.com/live/3954_468780224.m3u8"]},

{"name":"D_跑男韩","urls":["http://zzy789.xyz/douyu1.php?id=7298973"]},
{"name":"D_音乐s","urls":[
"http://live.m2.tv/hls3/stream.m3u8",
"http://de1se01.v2beat.live/playlist.m3u8",
"http://lb.streaming.sk/fashiontv/stream/chunklist.m3u8",
"http://lb.streaming.sk/fashiontv/stream/chunklist_w1702070444.m3u8",
"http://juyunlive.juyun.tv/live/24950198.m3u8"
]},

{"name":"H_张大仙688","urls":["http://epg.112114.xyz/huya/688"]},

{"name":"D_直播s","urls":[
"http://epg.112114.xyz/huya/520902",
"http://zzy789.xyz/douyu1.php?id=9173372",
"http://zzy789.xyz/douyu1.php?id=8732382"
]}
            ]
        },

        {
            "group":"影视轮播",
            "channels":[
{"name":"D_豆瓣高分","urls":["http://zzy789.xyz/douyu1.php?id=8770422"]},
{"name":"D_经典喜剧","urls":["http://zzy789.xyz/douyu1.php?id=9650887"]},
{"name":"D_都市喜剧","urls":["http://zzy789.xyz/douyu1.php?id=10240539"]},
{"name":"D_喜剧电影","urls":["http://zzy789.xyz/douyu1.php?id=9292492"]},

{"name":"D_胆小勿入","urls":["http://zzy789.xyz/douyu1.php?id=3637726"]},
{"name":"D_经典恐怖","urls":["http://zzy789.xyz/douyu1.php?id=1165374"]},
{"name":"D_丧尸鬼片","urls":["http://zzy789.xyz/douyu1.php?id=96577"]},
{"name":"D_悬疑专题","urls":["http://zzy789.xyz/douyu1.php?id=10395965"]},
{"name":"D_恐怖电影","urls":["http://zzy789.xyz/douyu1.php?id=310926"]},
{"name":"Q_恐怖影院","urls":["http://111.6.232.36/txpcdn.liveplay.egame.qq.com/live/3954_449390391.m3u8"]},
{"name":"D_奇妙博物馆","urls":["http://zzy789.xyz/douyu1.php?id=9409723"]},

{"name":"D_新片放映","urls":["http://zzy789.xyz/douyu1.php?id=3637765"]},
{"name":"D_华语经典","urls":["http://zzy789.xyz/douyu1.php?id=85894"]},
{"name":"D_米娅陪看","urls":["http://zzy789.xyz/douyu1.php?id=6537888"]},
{"name":"D_高帧武侠","urls":["http://zzy789.xyz/douyu1.php?id=6763930"]},
{"name":"D_经典国产","urls":["http://zzy789.xyz/douyu1.php?id=10515109"]},
{"name":"D_邵氏影院","urls":["http://zzy789.xyz/douyu1.php?id=4246519"]},
{"name":"D_粤语电影","urls":["http://zzy789.xyz/douyu1.php?id=1226741"]},

{"name":"周星驰","urls":["http://117.148.179.153/PLTV/88888888/224/3221231562/index.m3u8"]},
{"name":"D_周星驰","urls":["http://zzy789.xyz/douyu1.php?id=122402"]},
{"name":"Q_林正英","urls":["http://111.6.232.36/txpcdn.liveplay.egame.qq.com/live/3954_363783415.m3u8"]},
{"name":"D_刘德华","urls":["http://zzy789.xyz/douyu1.php?id=2516864"]},

{"name":"D_电影s","urls":[
"http://zzy789.xyz/douyu1.php?id=2516864",
"http://epg.112114.xyz/douyu/323876",
"http://148.70.143.24/cms/yslb/yunshitv/wangyouzhibo/douyu.php?tvplay=925724",
"http://148.70.143.24/cms/yslb/yunshitv/wangyouzhibo/douyu.php?tvplay=7701735",
"http://tx2play1.douyucdn.cn/live/122402rK7MO9bXSq.xs?uuid=",
"http://zzy789.xyz/douyu1.php?id=122402"
]},

{"name":"D_鬼吹灯s","urls":[
"http://zzy789.xyz/douyu1.php?id=9292503",
"http://zzy789.xyz/douyu1.php?id=7701735"
]},

{"name":"D_爱情公寓","urls":["http://zzy789.xyz/douyu1.php?id=2838296"]},
{"name":"D_家有儿女","urls":["http://zzy789.xyz/douyu1.php?id=6648727"]},

{"name":"D_老烟斗","urls":["http://zzy789.xyz/douyu1.php?id=2337939"]},

{"name":"D_说电影s","urls":[
"http://epg.112114.xyz/douyu/9986305",
"http://epg.112114.xyz/douyu/8651489",
"http://epg.112114.xyz/douyu/9338839"
]}

            ]
        },

        {
            "group":"动画频道",
            "channels":[

{"name":"D_海绵宝宝","urls":["http://zzy789.xyz/douyu1.php?id=3949681"]},
{"name":"D_大力水手","urls":["http://epg.112114.xyz/douyu/7620081"]},
{"name":"D_开心锤锤","urls":["http://epg.112114.xyz/douyu/9018297"]},
{"name":"D_沙雕动画","urls":["http://epg.112114.xyz/douyu/9505575"]},

{"name":"动漫轮播","urls":["http://117.148.179.160/PLTV/88888888/224/3221231568/index.m3u8"]},

{"name":"黑莓动画","urls":[
"http://39.134.67.6:80/ottrrs.hl.chinamobile.com/PLTV/88888888/224/3221225662/1.m3u8",
"http://39.134.67.7:80/ottrrs.hl.chinamobile.com/PLTV/88888888/224/3221225662/1.m3u8"
]}
            ]
        },

        {
            "group":"卫视频道",
            "channels":[
                {
                    "name":"东方卫视",
                    "urls":[
                        "http://39.135.138.59:18890/PLTV/88888910/224/3221225658/index.m3u8",
                        "http://39.135.138.59:18890/PLTV/88888910/224/3221225659/index.m3u8",
                        "http://39.135.46.246:6610/PLTV/77777777/224/3221225682/index.m3u8?hls",
                        "http://39.135.140.226:6410/PLTV/88888888/224/3221225489/2/index.m3u8?fmt=ts2hls",
                        "http://39.134.118.77/live.gq.miguvideo.com:8080/wd_r4/dfl/dongfangwshd/3000/index.m3u8?&encrypt=1"
                    ]
                },
                {
                    "name":"北京卫视FHD",
                    "urls":[
                        "http://39.134.115.163:8080/PLTV/88888910/224/3221225674/index.m3u8",
                        "http://39.135.138.60:18890/PLTV/88888910/224/3221225673/index.m3u8",
                        "http://39.134.118.77/live.gq.miguvideo.com:8080/ws_w/2018/bjws/bjws2000/2000/index.m3u8?&encrypt=1"
                    ]
                },

                {
                    "name":"浙江卫视",
                    "urls":[
                        "http://39.134.18.82/dbiptv.sn.chinamobile.com/PLTV/88888890/224/3221225798/index.m3u8$3M1080P",
                        "http://39.135.46.246:6610/PLTV/77777777/224/3221225695/index.m3u8?hls",
                        "http://39.134.67.2:80/ottrrs.hl.chinamobile.com/PLTV/88888888/224/3221225612/1.m3u8",
                        "http://39.135.140.226:6410/PLTV/88888888/224/3221225491/2/index.m3u8?fmt=ts2hls",
                        "http://39.134.115.163:8080/PLTV/88888910/224/3221225744/index.m3u8",
                        "http://39.135.138.60:18890/PLTV/88888910/224/3221225744/index.m3u8",
                        "http://39.134.118.77/live.gq.miguvideo.com:8080/wd_r2/cctv/zhejianghd/2500/index.m3u8?&encrypt=1"
                    ]
                },
                {
                    "name":"江苏卫视",
                    "urls":[
                        "http://39.135.138.59:18890/PLTV/88888910/224/3221225743/index.m3u8",
                        "http://39.134.18.82/dbiptv.sn.chinamobile.com/PLTV/88888890/224/3221225800/index.m3u8$3M1080P",
                        "http://117.148.179.160/PLTV/88888888/224/3221231447/index.m3u8",
                        "http://39.135.140.226:6410/PLTV/88888888/224/3221225488/2/index.m3u8?fmt=ts2hls",
                        "http://39.134.115.163:8080/PLTV/88888910/224/3221225743/index.m3u8",
                        "http://39.134.118.77/live.gq.miguvideo.com:8080/wd_r2/cctv/jiangsuhd/2500/index.m3u8?&encrypt=1"
                    ]
                },
                {
                    "name":"湖南卫视",
                    "urls":[
                        "http://39.134.18.82/dbiptv.sn.chinamobile.com/PLTV/88888890/224/3221225799/index.m3u8$3M1080P",
                        "http://39.135.138.60:18890/PLTV/88888910/224/3221225745/index.m3u8",
                        "http://39.135.138.59:18890/PLTV/88888910/224/3221225704/index.m3u8",
                        "http://111.40.196.9/PLTV/88888888/224/3221225521/index.m3u8",
                        "http://124.232.233.16:6610/000000001001/201500000067/index.m3u8?&version=v1.0&IASHttpSessionId=SLB2046220190906022827233263&AuthInfo=&m3u8_level=2",
                        "http://111.40.196.9/PLTV/88888888/224/3221225519/index.m3u8",
                        "http://39.135.46.246:6610/PLTV/77777777/224/3221225692/index.m3u8?hls",
                        "http://39.135.140.226:6410/PLTV/88888888/224/3221225490/2/index.m3u8?fmt=ts2hls",
                        "http://223.110.245.151/ott.js.chinamobile.com/PLTV/3/224/3221227698/index.m3u8$4M1080P",
                        "http://223.110.244.133:6610/gitv/live1/G_HUNAN-CQ/G_HUNAN-CQ/",
                        "http://39.134.118.77/live.gq.miguvideo.com:8080/wd-hunanhd-2500/index.m3u8?&encrypt=1",
                        "http://39.134.118.77/live.gq.miguvideo.com:8080/migu/kailu/hunanhd265/57/20191230/index.m3u8?&encrypt=1"
                    ]
                },
                {
                    "name":"CCTV-1综合",
                    "urls":[
"http://39.136.66.39/cdnrrs.gz.chinamobile.com/PLTV/88888888/224/3221225777/1/index.m3u8?fmt=ts2hls",
"http://117.148.179.155/PLTV/88888888/224/3221231468/index.m3u8",
"http://117.148.179.155/PLTV/88888888/224/3221231471/index.m3u8",
"http://39.135.34.150:8080/000000001000/1000000001000021973/1.m3u8?xtkg",
"http://39.135.138.60:18890/PLTV/88888910/224/3221225618/index.m3u8",
"http://39.135.138.59:18890/PLTV/88888910/224/3221225642/index.m3u8",
                        "http://39.134.115.163:8080/PLTV/88888910/224/3221225618/index.m3u8",
                        "http://39.135.138.58:18890/PLTV/88888888/224/3221225642/index.m3u8",
                        "http://39.134.118.77/live.gq.miguvideo.com:8080/migu/kailu/cctv1hd265/57/20191230/index.m3u8?&encrypt=1"
                    ]
                }
            ]
        },

      
        {
            "group":"测试频道",
            "channels":[
                {
                    "name":"澳門有線 CH1",
                    "urls":[
                        "http://61.244.22.4/ch1/ch1.live/playelist.m3u8"
                    ]
                },
                {
                    "name":"澳視澳門",
                    "urls":[
                        "http://61.244.22.4/ch1/ch1.live/index.m3u8"
                    ]
                },
                {
                    "name":"KBS Worlds",
                    "urls":[
                        "https://livecdn.fptplay.net/sdb/kbs_hls.smil/chunklist_b2500000.m3u8"
                    ]
                },
                {
                    "name":"HG2",
                    "urls":[
                        "http://necgokr2-724.acs.wecandeo.com/ms/2528/724/index_1.m3u8"
                    ]
                }
            ]
        }
    ],


"parses":[

/*
{"name":"点此自动解析","type":3,"url":"Demo"},
{"name":"并发","type":2,"url":"Parallel"},
{"name":"轮询","type":2,"url":"Sequence"}, 
*/

{"name":"默认并发","type":2,"url":"Parallel"},
   
/*自用解析整理*/    
{"name":"dj-vip123kan","type":1,"url":"http://api.vip123kan.vip/?url="},

{"name":"dj01OK","type":1,"url":"https://okjx.cc/?url="},
{"name":"dj02BL","type":1,"url":"https://vip.bljiex.com/?v="},
{"name":"dj03虾米","type":1,"url":"https://jx.xmflv.com/?url="},
{"name":"dj04虾米","type":1,"url":"https://nbjx.vip/?url="},
{"name":"dj05人人迷","type":1,"url":"https://jx.blbo.cc:4433/?url="},
{"name":"dj06云海","type":1,"url":"http://47.100.138.210:92/?url="},
{"name":"dj07Parwix","type":1,"url":"https://jx.parwix.com:4433/player/?url="},
{"name":"dj08诺迅","type":1,"url":"https://www.nxflv.com/?url="},
{"name":"dj09纯净","type":1,"url":"https://z1.m1907.cn/?jx="},
{"name":"dj10云端","type":1,"url":"https://sb.5gseo.net/?url="},
{"name":"dj11初恋","type":1,"url":"https://jx.xuanqi.pro/?url="},
{"name":"dj12","type":1,"url":"https://json.5lp.net/json.php?url="},
{"name":"dj14","type":1,"url":"http://api.diliktv.xyz/vip/jx.php?url="},

/*猫群解析收集*/
{"name":"mq02人人迷","type":1,"url":"https://jx.renrenmi.cc/?url="},
{"name":"mq10M3U8","type":1,"url":"https://jsap.attakids.com/?url="},
{"name":"mq24HuMao","type":1,"url":"https://app.okmedcos.com/4k/?url="},

/*六神解析收集*/
{"name":"ls龙腾(主)","type":1,"url":"https://languangyingshiziyuan.1080zy.top/longtengzy.php/?url="},
{"name":"ls雪人(主)","type":1,"url":"https://jx.zhanlangbu.com/json.php/?url="},

/*其他解析收集*/
{"name" : "腾讯云", "url" : "https://api.jhdyw.vip/?url="},
{"name" : "久看", "url" : "https://9kjx.com/?url="},
{"name" : "全民解析", "url" : "https://jx.quanmingjiexi.com/?url="},
{"name" : "Ckplayer", "url" : "https://www.ckplayer.vip/jiexi/?url="},
{"name" : "M3U8", "url" : "https://jx.m3u8.tv/jiexi/?url="},
{"name" : "盘古", "url" : "https://www.pangujiexi.cc/jiexi.php?url="},
{"name" : "H8", "url" : "https://www.h8jx.com/jiexi.php?url="},
{"name" : "维多", "url" : "https://jx.ivito.cn/?url="},
{"name" : "盘古云", "url" : "https://go.yh0523.cn/y.cy?url="},

{"name" : "17云", "url" : "https://www.1717yun.com/jx/ty.php?url="},
{"name" : "116", "url" : "https://jx.116kan.com/?url="},
{"name" : "200", "url" : "https://vip.66parse.club/?url="},
{"name" : "8090", "url" : "https://www.8090g.cn/?url="},
{"name" : "暮光解析", "url" : "https://muguang.mgtv.com.muguangys.com/jiexi.php?url="},
{"name" : "Parwix解析1", "url" : "https://vip.parwix.com:4433/player/?url="},
{"name" : "parwix解析2", "url" : "https://jx.parwix.com:4433/player/?url="},
{"name" : "lekanzyw", "url" : "https://bak.ojbkjx.com/?url="},
{"name" : "titan.mgtv", "type" : 1, "url" : "https://titan.mgtv.com.o8tv.com/jiexi/?url="},
{"name" : "高速接口1", "url" : "https://jsap.attakids.com/?url="},
{"name" : "4kdv", "type" : 1, "url" : "https://jx.4kdv.com/?url="},
{"name" : "B站解析2", "url" : "https://www.cuan.la/m3u8.php?url="},
{"name" : "Mao解析", "url" : "https://qd.hxys.tv/m3u8.php?url="},
{"name" : "17kyun.zh188", "type" : 1, "url" : "https://1717yun.com.zh188.net/0828/?url="},
{"name" : "17kyun", "type" : 1, "url" : "http://17kyun.com/api.php?url="},
{"name" : "默认", "type" : 1, "url" : "http://api.u1o.net/?url="},
{"name" : "月亮", "type" : 1, "url" : "https://vip.jianjians.com/?url="},
{"name" : "乐多资源", "type" : 1, "url" : "https://api.leduotv.com/wp-api/ifr.php?isDp=1&vid="},
{"name" : "ckmov", "type" : 1, "url" : "https://www.ckmov.vip/api.php?url="},
{"name" : "SSAMAO", "type" : 1, "url" : "https://www.ssamao.com/jx/?url="},
{"name" : "无极", "type" : 1, "url" : "https://da.wujiys.com/?url="},
{"name" : "618G", "type" : 1, "url" : "https://jx.618g.com/?url="},
{"name" : "福星", "type" : 1, "url" : "https://jx.popo520.cn/jiexi/?url="},
{"name" : "RDHK", "type" : 1, "url" : "https://jx.rdhk.net/?v="},
{"name" : "解析la", "type" : 1, "url" : "https://api.jiexi.la/?url="},
{"name" : "久播", "type" : 1, "url" : "https://jx.jiubojx.com/vip.php?url="},
{"name" : "九八", "type" : 1, "url" : "https://jx.youyitv.com/?url="},
{"name" : "乐喵", "type" : 1, "url" : "https://jx.hao-zsj.cn/vip/?url="},
{"name" : "MUTV", "type" : 1, "url" : "https://jiexi.janan.net/jiexi/?url="},
{"name" : "明日", "type" : 1, "url" : "https://jx.yingxiangbao.cn/vip.php?url="},
{"name" : "磨菇", "type" : 1, "url" : "https://jx.wzslw.cn/?url="},
{"name" : "OK", "type" : 1, "url" : "https://okjx.cc/?url="},
{"name" : "小蒋", "type" : 1, "url" : "https://www.kpezp.cn/jlexi.php?url="},
{"name" : "小狼", "type" : 1, "url" : "https://jx.yaohuaxuan.com/?url="},
{"name" : "智能", "type" : 1, "url" : "https://vip.kurumit3.top/?v="},
{"name" : "月亮", "type" : 1, "url" : "https://api.yueliangjx.com/?url="},
{"name" : "云端", "type" : 1, "url" : "https://jx.ergan.top/?url="},
{"name" : "66", "type" : 1, "url" : "https://api.3jx.top/vip/?url="},
{"name" : "云析", "type" : 1, "url" : "https://jx.yparse.com/index.php?url="},
{"name" : "乐多解析", "type" : 1, "url" : "https://ldy.jx.cn/wp-api/ifr.php?vid="},
{"name" : "久播", "url" : "https://jx.jiubojx.com/vip/?url="},
{"name" : "U猫", "url" : "http://jiex.cf/?url="},
{"name" : "爱跟", "url" : "https://vip.2ktvb.com/player/?url="},
{"name" : "CHok", "url" : "https://www.gai4.com/?url="},
{"name" : "冰豆", "url" : "https://api.qianqi.net/vip/?url="},
{"name" : "大白", "url" : "https://api.myzch.cn/?url="},
{"name" : "大幕", "url" : "https://jx.52damu.com/dmjx/jiexi.php?url="},
{"name" : "跟剧", "url" : "https://www.5igen.com/dmplayer/player/?url="},
{"name" : "可乐", "url" : "https://jx.keleapi.com/?url=", "t" : "m"},
{"name" : "LE", "url" : "https://lecurl.cn/?url="},
{"name" : "懒猫", "url" : "https://api.lanmaody.com/dm/?url=", "t" : "m"},
{"name" : "诺诺", "url" : "https://www.ckmov.com/?url="},
{"name" : "诺讯", "url" : "https://www.nxflv.com/?url="},
{"name" : "PM", "url" : "https://www.playm3u8.cn/jiexi.php?url="},
{"name" : "奇米", "url" : "https://qimihe.com/?url="},
{"name" : "思云", "url" : "https://jx.ap2p.cn/?url="},
{"name" : "思古", "url" : "https://api.sigujx.com/?url="},
{"name" : "思古2", "url" : "https://api.bbbbbb.me/jx/?url="},
{"name" : "淘电影", "url" : "https://jx.vodjx.top/vip/?url="},
{"name" : "听乐", "url" : "https://jx.dj6u.com/?url=", "t" : "m"},
{"name" : "云点播", "url" : "https://api.iopenyun.com:88/vip/?url="},
{"name" : "蚂蚁兄弟", "url" : "https://daili.mayixiongdi.cn/?url="},
{"name" : "江湖D", "url" : "http://jx.zhiaiyy.top/?url="},
{"name" : "1080", "url" : "http://159.75.133.231:1788/?key=1&url="},
{"name" : "融兴", "url" : "https://test.rongxingvr.com/test/?url="},
{"name" : "萌瓜", "url" : "https://dm.2g88.vip/?url="},
{"name" : "爱解", "url" : "https://jiexi.t7g.cn/?url="},
{"name" : "09", "url" : "https://jx.09tv.top/bd/?url="},
{"name" : "清莲", "url" : "https://www.qinglyy.com/m3u8/?url="},
{"name" : "遇见", "url" : "https://jx.yujiannk.com/?url="},
{"name" : "渐渐", "url" : "https://titan.mgtv.com.janan.net:4433/mgtv1206/?url="},
{"name" : "娱乐", "url" : "https://vip.anje.cn/?url="},
{"name" : "安逸", "url" : "http://www.mgtv.com.wchulian.com.cn/player/analysis.php?v="},
{"name" : "云云", "url" : "http://159.75.133.231:81/jiexi/?url="},
{"name" : "啊茹竹嘎", "url" : "http://k.auuyruyc.com/player/?url="},
{"name" : "初心", "url" : "https://player.5znn.pro/jiexi.php?url="},
{"name" : "段友.日批", "url" : "https://jx.ns360.cn/1080/jiexi/?url="},
{"name" : "暮光", "url" : "https://www.mgtv.com.muguangys.com/jiexi1.php?url="},
{"name" : "瓜皮", "url" : "http://jxx.dijiaxia.com/?url="},
{"name" : "PAR", "url" : "https://jx.ihuikr.com/player/?url="},
{"name" : "乐喵", "url" : "http://jx.hao-zsj.cn/vip/?url="},
{"name" : "优全", "url" : "https://jx.xmyun.xyz/?url="},
{"name" : "万福", "url" : "https://jx.wfy4.com/?url="},
{"name" : "蓝猫", "url" : "https://jx.daidaitv.top:43810/?url="},
{"name" : "樱花", "url" : "https://buaon.xyz/?url="},
{"name" : "白玉", "url" : "https://jx.baiyu.buzz/?url="},
{"name" : "白玉B", "url" : "https://jx.baiyu.buzz/bb/?url="},
{"name" : "白玉C", "url" : "https://jx.baiyu.buzz/cc/?url="},
{"name" : "淘影A", "url" : "http://jx.1080jx.top/vipjx/?url="},
{"name" : "淘影B", "url" : "http://jx.1080jx.top/jxvip/?url="},
{"name" : "淘影C", "url" : "http://jx.1080jx.top/m3u8/?url="},
{"name" : "淘影D", "url" : "http://jx.1080jx.top/vip/?url="},
{"name" : "淘影E", "url" : "http://jx.1080jx.top/api/?url="},
{"name" : "淘影F", "url" : "http://jx.1080jx.top/jiexi/?url="},
{"name" : "金j", "url" : "http://jjxx.me/?url="},
{"name" : "八一", "url" : "http://vip.8bys.cn/?url="},
{"name" : "宝莲", "url" : "http://danmu.8old.cn/vip/?url="},
{"name" : "追剧达人", "url" : "https://vip123kan.vip/m3u8.php?url="},
{"name" : "速搜影院", "url" : "http://vip.susou.tv/player/?url="},
{"name" : "66parse", "url" : "http://vip.66parse.club/?url="},
{"name" : "八二", "url" : "http://jx2.8bys.cn/m3u8.php?url="},
{"name" : "M2090", "url" : "https://m2090.com/?url="},
{"name" : "MW0", "url" : "https://jx.mw0.cc/?url="},
{"name" : "番茄弹幕解析", "url" : "http://jiexi.fqzy.cc/player/jx.php?url="},
{"name" : "660e", "url" : "https://660e.com/?url="},
{"name" : "旧城影视", "url" : "https://jx.9eng.cn/?url="},
{"name" : "七哥", "url" : "https://jx.mmkv.cn/tv.php?url="},
{"name" : "盘古", "url" : "http://www.pangujiexi.cc/jiexi.php?url="},
{"name" : "Mao全网解析", "url" : "http://lecurl.cn/?url="},
{"name" : "YiTV", "url" : "http://jiexi.us/?url="},
{"name" : "猪蹄", "url" : "https://jx.iztyy.com/svip/?url="},
{"name" : "小狼云", "url" : "https://jx.xiaolangyun.com/?url="},
{"name" : "云解析", "url" : "https://jx.aidouer.net/?url="},
{"name" : "线路二(国外)", "url" : "https://jx.ppflv.com/?url="},
{"name" : "线路三(备用)", "url" : "https://jx.duzheba.cn/?url="},
{"name" : "TNVIP云播放", "url" : "http://www.33tn.cn/?url="},
{"name" : "(带选集的二次解析)", "url" : "https://parse.xymov.net/?url="},
{"name" : "m3u8", "url" : "http://jx.rdhk.net/?v="},
{"name" : "智能接口", "url" : "http://jiexi.30dian.cn/?url="},
{"name" : "云栖", "url" : "https://www.yq52.cn/film/?url="},
{"name" : "神马", "url" : "https://jxx.smys8.cn/index.php?url="},
{"name" : "云波", "url" : "https://zy.aoxtv.com/?url="},
{"name" : "久已", "url" : "https://www.91jxs.com/jiexi/?url="},
{"name" : "盒子", "url" : "http://jx5.178du.com/p1/?url="},
{"name" : "七彩", "url" : "https://www.xymav.com/?url="},
{"name" : "ELW", "url" : "https://jx.elwtc.com/vip/?url="},
{"name" : "无名", "url" : "https://www.administratorw.com/video.php?url="},
{"name" : "33t", "url" : "https://www.33tn.cn/?url="},
{"name" : "夷狄", "url" : "https://api.1dior.cn/analysis/123/index.php?uid=1428&my=afkruDFIYZ&url="},
{"name" : "柠檬", "url" : "https://youku.jianzhengobey.top/yueliang.php?v="},
{"name" : "江湖F", "url" : "http://jx.yhys.icu:4433/?url="},
{"name" : "江湖B", "url" : "https://123.xxgcx.cn:4433/jianghu.php?url="},
{"name" : "leeleo", "url" : "https://www.mgtv.com.leeleo.cn/nmm/player/?url="},
{"name" : "酷吧", "url" : "https://kuba.renrenmi.cc:2266/api/?key=1PhqM8xRCbmfgwmcE2&url="},
{"name" : "高天", "url" : "https://vip.gaotian.love/api/?key=sRy0QAq8hqXRlrEtrq&url="},
{"name" : "ok", "url" : "http://9ok.co/?url="},
{"name" : "干饭(人人迷)", "url" : "https://jx.zui.cm/?url="},
{"name" : "66影视", "url" : "https://2.66movie.top/player/?url="},
{"name" : "麦子", "url" : "http://api.maizimall.com/index.php?url="},
{"name" : "云海正版", "url" : "https://jxjx.jushiys.co/player/ckplayer.php?url="},
{"name" : "一起百度", "url" : "https://jx5.178du.com/8090/jiexi/?url="},
{"name" : "夜幕", "url" : "https://www.yemu.xyz/?url="},
{"name" : "明日解析", "url" : "https://www.qianyicp.com/vip/vip_p3.php?url="},
{"name" : "明日解析2", "url" : "https://www.qianyicp.com/jiexi/index.php?url="},
{"name" : "林志远", "url" : "https://jiexi.linzhiyuan.xyz/jiexi/?url="},
{"name" : "淘影1080", "url" : "https://jx.1080jx.top/jx/?url="},
{"name" : "飞飞智能", "url" : "https://y.9dan.cc/?v="},
{"name" : "步步高", "url" : "https://jx.xihujx.com/index.php?url="},
{"name" : "飞捷", "url" : "https://vip.fj6080.xyz/player/?url="},
{"name" : "4k", "url" : "https://vip.jx4k.com/vip/?url="},
{"name" : "航海锚", "url" : "https://vip.xrff.xyz/?url="},
{"name" : "Mao", "url" : "https://www.mtosz.com/m3u8.php?url="},
{"name" : "1717云备用", "url" : "https://www.1717yun.com/beiyong/?url="},
{"name" : "尊享", "url" : "https://player.maqq.cn/?url="},
{"name" : "星驰", "url" : "https://vip.swuii.top/?url="},
{"name" : "优惠福利购", "url" : "http://www.youhuifuligou.com/json/?id=1&url="},
{"name" : "盘古json", "url" : "https://json.pangujiexi.com:12345/json.php?url="},
{"name" : "你爹科技", "type" : 1, "url" : "http://cache.languang.icu:88/didi.php?url="},
{"name" : "百度解析", "type" : 1, "url" : "https://bdjx.shoujick.com/json1231/?url="},
{"name" : "江湖科技2", "type" : 1, "url" : "http://play.bichangzw.cn/jianghu/json/?url="},
{"name" : "影视工厂", "url" : "https://jx.ysgc.xyz/?url="},
{"name" : "Json.VodJX", "url" : "http://admin.vodjx.top/json.php?url=", "type" : 1},
{"name" : "VodJX1", "url" : "https://api.vodjx.top/?url="},
{"name" : "VodJX2", "url" : "https://jx.vodjx.top/jiexi.php?url="},
{"name" : "ok3389", "url" : "https://api.okjx.cc:3389/jx.php?url="},
{"name" : "游艺", "url" : "https://api.u1o.net/?url="},
{"name" : "高清1", "type" : 0, "url" : "https://titan.mgtv.com.jumi.tv/player/?url="},
{"name" : "高清2", "type" : 0, "url" : "https://dmku.dijiaxia.com/?url="},
{"name" : "高清4", "type" : 0, "url" : "http://an61.com/jx/vip?v="},
{"name" : "娃娃", "url" : "http://frog.pinellia.xyz/jx/?url="},
{"name" : "人人迷", "url" : "https://jx.renrenmi.cc/?url="},
{"name" : "追剧达人3", "type" : 1, "url" : "http://jx.vipmv.co/json3/?url="}

				  			  
       ],



     "flags":["youku","qq","iqiyi","qiyi","letv","sohu","tudou","pptv","mgtv","wasu","bilibili","duoduozy","longteng","renrenmi","优酷","芒果","腾讯","爱奇艺","奇艺","ltnb","rx","xueren","xfyun","ziqie","wuduzy","CL4K","xuanfeng","1920l"
  ],
 
  
 
  "ijk": [
    {
      "group": "软解码",
      "options": [
        {
          "category": 4,
          "name": "opensles",
          "value": "0"
        },
        {
          "category": 4,
          "name": "overlay-format",
          "value": "842225234"
        },
        {
          "category": 4,
          "name": "framedrop",
          "value": "1"
        },
        {
          "category": 4,
          "name": "soundtouch",
          "value": "1"
        },
        {
          "category": 4,
          "name": "start-on-prepared",
          "value": "1"
        },
        {
          "category": 1,
          "name": "http-detect-range-support",
          "value": "0"
        },
        {
          "category": 1,
          "name": "fflags",
          "value": "fastseek"
        },
        {
          "category": 2,
          "name": "skip_loop_filter",
          "value": "48"
        },
        {
          "category": 4,
          "name": "reconnect",
          "value": "1"
        },
        {
          "category": 4,
          "name": "max-buffer-size",
          "value": "5242880"
        },
        {
          "category": 4,
          "name": "enable-accurate-seek",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec-auto-rotate",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec-handle-resolution-change",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec-hevc",
          "value": "0"
        }
      ]
    },
    {
      "group": "硬解码",
      "options": [
        {
          "category": 4,
          "name": "opensles",
          "value": "0"
        },
        {
          "category": 4,
          "name": "overlay-format",
          "value": "842225234"
        },
        {
          "category": 4,
          "name": "framedrop",
          "value": "1"
        },
        {
          "category": 4,
          "name": "soundtouch",
          "value": "1"
        },
        {
          "category": 4,
          "name": "start-on-prepared",
          "value": "1"
        },
        {
          "category": 1,
          "name": "http-detect-range-support",
          "value": "0"
        },
        {
          "category": 1,
          "name": "fflags",
          "value": "fastseek"
        },
        {
          "category": 2,
          "name": "skip_loop_filter",
          "value": "48"
        },
        {
          "category": 4,
          "name": "reconnect",
          "value": "1"
        },
        {
          "category": 4,
          "name": "max-buffer-size",
          "value": "5242880"
        },
        {
          "category": 4,
          "name": "enable-accurate-seek",
          "value": "0"
        },
        {
          "category": 4,
          "name": "mediacodec",
          "value": "1"
        },
        {
          "category": 4,
          "name": "mediacodec-auto-rotate",
          "value": "1"
        },
        {
          "category": 4,
          "name": "mediacodec-handle-resolution-change",
          "value": "1"
        },
        {
          "category": 4,
          "name": "mediacodec-hevc",
          "value": "1"
        }
      ]
    }
  ],
   "ads": [
    "mimg.0c1q0l.cn",
    "www.googletagmanager.com",
    "www.google-analytics.com",
    "mc.usihnbcq.cn",
    "mg.g1mm3d.cn",
    "mscs.svaeuzh.cn",
    "cnzz.hhttm.top",
    "tp.vinuxhome.com",
    "cnzz.mmstat.com",
    "www.baihuillq.com",
    "s23.cnzz.com",
    "z3.cnzz.com",
    "c.cnzz.com",
    "stj.v1vo.top",
    "z12.cnzz.com",
    "img.mosflower.cn",
    "tips.gamevvip.com",
    "ehwe.yhdtns.com",
    "xdn.cqqc3.com",
    "www.jixunkyy.cn",
    "sp.chemacid.cn",
    "hm.baidu.com",
    "s9.cnzz.com",
    "z6.cnzz.com",
    "um.cavuc.com",
    "mav.mavuz.com",
    "wofwk.aoidf3.com",
    "z5.cnzz.com",
    "xc.hubeijieshikj.cn",
    "tj.tianwenhu.com",
    "xg.gars57.cn",
    "k.jinxiuzhilv.com",
    "cdn.bootcss.com",
    "ppl.xunzhuo123.com",
    "xomk.jiangjunmh.top",
    "img.xunzhuo123.com",
    "z1.cnzz.com",
    "s13.cnzz.com",
    "xg.huataisangao.cn",
    "z7.cnzz.com",
    "xg.huataisangao.cn",
    "z2.cnzz.com",
    "s96.cnzz.com",
    "q11.cnzz.com",
    "thy.dacedsfa.cn",
    "xg.whsbpw.cn",
    "s19.cnzz.com",
    "z8.cnzz.com",
    "s4.cnzz.com",
    "f5w.as12df.top",
    "ae01.alicdn.com",
    "www.92424.cn",
    "k.wudejia.com",
    "vivovip.mmszxc.top",
    "qiu.xixiqiu.com",
    "cdnjs.hnfenxun.com",
    "cms.qdwght.com"
  ]
}
