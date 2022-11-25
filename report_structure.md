##  作品题目：【健康/量测应用类】

面向中老年人基于智能床垫的智能睡眠优化装置

or

基于睡眠监测体系的中老年人睡眠监测智能床垫

or

？？



##  作品摘要

鉴于当今国际社会老龄化现象日趋严峻，且市场上面向中老年人健康监测产品种类的不足，本团队提出一款基于系列健康监测传感器及睡眠数据深度分析算法的智能床垫，以实现面向中老年群体的系统睡眠健康监测。本系统通过红外视觉分析，离散化布局压力传感器监测、基于气囊的床垫硬度调节等手段提供生命体征监测、睡眠生物数据收集分析，智能化睡眠环境优化等功能，通过云端向多元化终端提供操作接口，致力于为中老年用户群体提供优良、智能化的睡眠监测服务及睡眠体验的改善。以下将对项目研发意义进行剖析，并论证项目方案的可行性及实现手段。

Due to the increasingly serious aging phenomenon in contemporary society, and the lack of health monitoring products for middle-aged and elderly people on the market, our team proposed a smart mattress based on a series of health monitoring sensors and deep analysis algorithms for sleep data, in order to realize the health benefits for middle-aged and elderly people. Systematic sleep health monitoring for populations. The system provides vital signs monitoring, sleep biological data collection and analysis, intelligent sleep environment optimization and other functions through infrared visual analysis, discrete layout pressure sensor monitoring, airbag-based mattress hardness adjustment, etc., and provides operations to multiple terminals through the cloud Interface, dedicated to providing excellent and intelligent sleep monitoring services and improving sleep experience for middle-aged and elderly users. The following part will illustrate the significance of research and development, and demonstrate the feasibility and meaning of realization of the whole project.

## 一、绪论

### 1.1. 研究背景与意义

经本团队的调研分析，定位于当今全球发达地区老龄化日益严峻的时代，团队成员获悉健康监测类产品普遍还存在智能化程度偏低，涵盖面相对较窄等不足。本团队旨在提出并测试一种基于系列健康监测传感器及睡眠数据深度分析算法的智能床垫。该项目在丰富面向中老年群体健康监测产品的功能，拓展健康监测产品的覆盖领域，优化中老龄用户对健康监测产品的智能化体验、及为睡眠健康临床医学提供有用临床生命体征数据等方面均有重要意义。此外，本团队项目的设计及定位亦响应了国家《“十四五”健康老龄化规划》《“十四五”国家老龄事业发展和养老服务体系规划》等若干政策需求，具有良好的时效性及可持续性。

### 1.2. 市场可行性及研究现状

本团队产品的定位主要面向中老龄群体，据本团队的实际市场调研分析，当代中老龄群体对智能健康监测类产品需求较广，同时具备操作简单，功能广泛，深入生活的健康监测类产品需求广泛。此外，中老年人健康亦是临床医学的关注热点，在保护用户隐私的前提下，一套存在收集大量睡眠临床生命体征数据潜力的健康监测系统亦对于老年人健康临床医学的发展有不可或缺作用。可见本团队开发的系统在对于受众群体及临床医学均有较大作用，市场潜力较广。

目前市面上的健康监测类产品大多功能局限单一，智能化解决方案相对缺乏，较少跨类别生命体征联合监测的应用案例。本团队的项目定位补全了这一市场空白，具有较强新颖性。

### 1.3. 研究内容及创新点

本文以下部分将从作品设计及功能，系统方案与原理两大部分展开叙述。其中作品设计及功能主要剖析本产品的功能与指标（含创新点的具体实现）及产品外观设计。另外，系统方案与原理侧重于论述本团队对系统方案的论证，阐述系统流程、模块机制及对展开的产品测试实验过程及根据实验数据展开的系统分析。

本项目的创新点主要简述为如下若干点：基于ITO发热膜及半导体制冷的床垫表面温度智能化控制、基于柔性光导纤维的床垫全域紫外线除螨、基于压力传感器及红外视觉分析的睡眠数据监测。（创新点实现过程详见本文3.1部分）。



## 二、作品设计及功能



### 3.1 系统功能与指标【参考省电报告书】

1.基于ITO发热膜及半导体制冷的床垫表面温度智能化控制

具体实现功能：

本系统基于在床垫表面离散化布局AHT20温湿度传感器对床垫表面温度进行监测，并以此为依据提供全自动化床垫表面温度调节功能。此外，本系统根据临床睡眠环境温度数据分析【参考文献】（15.6-19.4摄氏度为人体最适睡眠环境温度)提供全时段床垫表面温度智能调节功能。其中，本团队采用与床垫融合度较高的柔性器件ITO发热膜作为发热组件，采用相对成熟且高效的半导体制冷技术进行制冷。综上，就系统功能而言，本团队向用户提供基于AHT20数据实现的温度自适应调节模式和基于临床数据实现的跨时段温度智能调节模式，前者侧重根据环境温度将床垫表面温度维持在人体最适温这一动态平衡状态，后者侧重根据临床数据优化夜间不同时段的温度设定以实现温度和人体略变体温的最优化匹配。

实现指标：

根据参考文献【】所提供的睡眠最适环境温度临床数据，本团队在经过一定的实验测试后认定15.6-19.4摄氏度为人体最适睡眠环境温度，并以此为依据根据不同时段调节温度从而实现环境温与人体温度的最优化搭配。

对于ITO型电阻型发热膜的参数要求如下：薄层电阻为 5 至 200 Ω/㎡，透光度高于80%~85%，上电小于5秒即可达到设定温度(50℃及以下)，最高耐温更可达到120℃，电压设定由1.5V~380V，功率不小于0.1W每平方厘米

对于半导体制冷片的参数要求如下：制冷最低温大于-30摄氏度，额定电压12-24V，电流10-15A，重量小于0.5kg，总厚度小于15cm



2.基于气囊的床垫软硬个性化调节

具体实现功能：

本系统通过分布于床垫下方的分立内嵌式气囊提供床垫局部软硬个性化调节的功能，用户可以根据使用需求对床垫的局部调节软硬层度，以满足更优的个性化睡眠需求。系统提供微型静音气泵对气囊进行充放气，操作手段有客户端应用程序，手势控制及语言识别。

实现指标：

展示品实验的气囊数不少于4个。微型气泵输入电压区间为DC-22-27V，配置过热保护，过载保护，反接保护，欠压过压保护等功能。



3.基于柔性光导纤维的床垫全域紫外线除螨

具体实现功能：

以布局于床垫下方的紫外线LED作为光源，通过大量杂散分布式光导纤维将紫外线上引至床垫内部及床垫。其中，位于床垫下方设备区的光导纤维采用全封闭式遮光材料，隔绝紫外线的外泄；位于床垫内部及表面的光导纤维采用半透光材质外壳，从而使紫外光源在床垫内部及表面发散化照射。对于控制方式，系统提供无人时段自动执行消毒和必要时的手动开启消毒。

实现指标：

光导纤维直径约为5mm-1cm，紫外光源总功率小于20W



4.基于光导纤维的床垫夜间辅助LED照明



5.基于多传感器及视觉与声音分析的睡眠数据监测

**具体实现功能：**

多传感器：以布局于床垫下方的压力传感器对人体在床垫上的翻身次数，人体脉搏。其中，压力传感器能够判断人体是否在床上，并通过压力变化判断人体是否处于深度睡眠状态，并监测翻身次数。

视觉分析：对人体睡眠数据进行监测，并上传云端。

**实现指标：**

压力传感器面积约为0.4*0.5m



6.基于麦克风及声音处理算法的呼吸状态分析

7.基于生命体征实时监测的**应急报警系统**

8.基于云端的睡眠数据分析及睡眠建议智能化推送

9.基于云服务器的语音交互API与智能化手势识别

**具体实现功能：**

为响应疫情时期减少不必要接触的防疫号召，我们提供非接触式、多元化的人机交互手段，用户可以通过语音识别或手势对系统进行控制，对于复杂的控制系统支持手机端控制，避免了交互手段过于繁琐、出错率高的缺陷。

**实现指标：**

为保证多元化人机交互的效率与准确性，要求语音识别模块在理想实验（输入语音清晰）情形下达到95%的识别准确性，系统反馈时间不得超过50ms。对于手势识别功能，要求摄像头识别范围内的基础手势能完成对系统默认若干种光照模式的切换的控制效果。



### 3.2 系统外观设计

### 

## 三、系统方案与原理

### 4.1系统方案论证【！需特别注意：对指定HT单片机使用的位置、负担功能等要有清楚说明】

本团队选用HT32F52352 (ESK32-30501S开发板)及树莓派4B作为系统的核心控制器，选用ESP32或ESP8266_NODE模块作为物联网通信手段，使用基于云端服务器的MQTT、HTTP或Socket通信协议实现两个核心控制器无线通讯。对此，HT32F52352 (ESK32-30501S开发板)承担控制的核心机能，直接控制系统中除视听觉组件外的所有传感器，通过串口通信与WIFI模块ESP32实现通讯从而接入物联网。其中，项目运用的传感器包括AHT20温湿度传感器、RFP602电阻型薄膜压力传感器、索爱MK3麦克风及CSI摄像头等。系统通过树莓派4B结合摄像头及其麦克风模块收集语音及手势控制指令通过云端发至HT32F52352实现人机交互控制。此外，ESP32亦通过云端收集来自其他智能化终端的用户控制命令，从而实现对微型气泵、紫外线光源等器件的直接控制。本团队所展示的比例模型中，除部分传感器外的所有控制器件均置于床垫下方。

### 4.2 系统硬件框图

### 4.3 系统软件流程

### 4.4 主要模块机制【阐述嵌入式部分的模块及硬件模块，参照省电报告书】

### 4.5 系统调试数据【省电报告书的精简，只阐述必要的模块及整体】



### 附录及参考文献

- 1.

  Joseph, D., Chong, N. W., Shanks, M. E., Rosato, E., Taub, N. A., Petersen, S. A., Symonds, M. E., Whitehouse, W. P., & Wailoo, M. (2015). Getting rhythm: how do babies do it?. Archives of disease in childhood. Fetal and neonatal edition, 100(1), F50–F54.https://doi.org/10.1136/archdischild-2014-306104

- 2.

  Del Bene VE. Temperature. In: Walker HK, Hall WD, Hurst JW, editors. Clinical Methods: The History, Physical, and Laboratory Examinations. 3rd edition. Boston: Butterworths; 1990. Chapter 218. Retrieved October 5, 2020, fromhttps://www.ncbi.nlm.nih.gov/books/NBK331/

- 3.

  Harding, E. C., Franks, N. P., & Wisden, W. (2020). Sleep and thermoregulation. Current opinion in physiology, 15, 7–13.https://doi.org/10.1016/j.cophys.2019.11.008

- 4.

  Lok, R., van Koningsveld, M. J., Gordijn, M., Beersma, D., & Hut, R. A. (2019). Daytime melatonin and light independently affect human alertness and body temperature. Journal of pineal research, 67(1), e12583.https://doi.org/10.1111/jpi.12583

- 5.

  Kräuchi K. (2007). The thermophysiological cascade leading to sleep initiation in relation to phase of entrainment. Sleep medicine reviews, 11(6), 439–451.https://doi.org/10.1016/j.smrv.2007.07.001

- 6.

  Fujii, H., Fukuda, S., Narumi, D., Ihara, T., & Watanabe, Y. (2015). Fatigue and sleep under large summer temperature differences. Environmental research, 138, 17–21.https://doi.org/10.1016/j.envres.2015.02.006

- 7.

  Kräuchi, K., Fattori, E., Giordano, A., Falbo, M., Iadarola, A., Aglì, F., Tribolo, A., Mutani, R., & Cicolin, A. (2018). Sleep on a high heat capacity mattress increases conductive body heat loss and slow wave sleep. Physiology & behavior, 185, 23–30.https://doi.org/10.1016/j.physbeh.2017.12.014

- 8.

  McHill, A. W., Smith, B. J., & Wright, K. P., Jr (2014). Effects of caffeine on skin and core temperatures, alertness, and recovery sleep during circadian misalignment. Journal of biological rhythms, 29(2), 131–143.https://doi.org/10.1177/0748730414523078

- 9.

  Komagata, N., Latifi, B., Rusterholz, T., Bassetti, C., Adamantidis, A., & Schmidt, M. H. (2019). Dynamic REM Sleep Modulation by Ambient Temperature and the Critical Role of the Melanin-Concentrating Hormone System. Current biology : CB, 29(12), 1976–1987.e4.https://doi.org/10.1016/j.cub.2019.05.009

- 10.

  Okamoto-Mizuno, K., & Mizuno, K. (2012). Effects of thermal environment on sleep and circadian rhythm. Journal of physiological anthropology, 31(1), 14. https://doi.org/10.1186/1880-6805-31-14

- 11.

  Kuo, T. B., Hong, C. H., Hsieh, I. T., Lee, G. S., & Yang, C. C. (2014). Effects of cold exposure on autonomic changes during the last rapid eye movement sleep transition and morning blood pressure surge in humans. Sleep medicine, 15(8), 986–997.https://doi.org/10.1016/j.sleep.2014.03.022

- 12.

  Haghayegh, S., Khoshnevis, S., Smolensky, M. H., Diller, K. R., & Castriotta, R. J. (2019). Before-bedtime passive body heating by warm shower or bath to improve sleep: A systematic review and meta-analysis. Sleep medicine reviews, 46, 124–135.https://doi.org/10.1016/j.smrv.2019.04.008

  