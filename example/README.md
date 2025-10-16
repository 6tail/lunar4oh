## 公历转农历示例

    // install
    ohpm i lunar4oh
     
    // import
    import {Solar} from 'lunar4oh';
     
    const solar = Solar.fromYmd(1986, 5, 29);
     
    // 1986-05-29 00:00:00 星期四 双子座
    console.log(solar.toFullString());
     
    // 一九八六年四月廿一 丙寅(虎)年 癸巳(蛇)月 癸酉(鸡)日 子(鼠)时 纳音[炉中火 长流水 剑锋金 桑柘木] 星期四 北方玄武 星宿[斗木獬](吉) 彭祖百忌[癸不词讼理弱敌强 酉不会客醉坐颠狂] 喜神方位[巽](东南) 阳贵神方位[巽](东南) 阴贵神方位[震](正东) 福神方位[兑](正西) 财神方位[离](正南) 冲[(丁卯)兔] 煞[东]
    console.log(solar.getLunar().toFullString());
