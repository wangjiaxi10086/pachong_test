Python����д��Ư�����������1

https://blog.csdn.net/weixin_36604953/article/details/78156605

����������ѧϰȦ�ӵ�ͬѧ���ܶ����涼�������ţ��������һ���ߴ��ϵĶ������·�����񹦺�Ǭ����Ų��һ�����ͱ���˵�����ӻ����桱���͸о��ر��бƸ񣬵����ֲ�֪�Ӻ����֣������������Ҿ���һ�����������沢�����أ�Ҳ���߼�����һ���ǳ������ֺ����յĶ�������Ȼ������Ҳ�кܶ�ӣ�Ҳ�кܶ�ϸ�ڣ�չ��˵�Ļ���ʵҲ�����ӵģ���������ģʽ����·�Ͱ����������С��Ĳ��ͣ���֤������������Ҫ�����ݣ���

һ������£������Ϊ���֣�һ���Ǿ�̬���棬һ���Ƕ�̬���棬��ν��̬���棬���Ǵ󲿷���Ϣ������������Ҫ����Щ��Ϣ����д��html�����еģ�����̬����һ�㶼��д��һ��json�ĵ��У���ô˵���ܲ�̫��׼��������ѧ���������⼴�ɣ���ƪ���ͽ����������Ծ�̬���棬��һƪ���ὲ�⶯̬���档

����һ�䣬����������ʵ��Python2�û�����������Ҳ�ĵ�Python3�ˣ������µĿ����Python2�����ȼ��ݣ�Ȼ��Ҫ���þò���Python3�м��ɣ�������ȫ���õ��ģ�Python2���ˣ�Python3���վͻἯ�ɣ�Python3Ҳ���ڱ��뷽���ṩ����������Ƽ�����ֱ�Ӵ�Python3���֣���Ȼ������û��ʲô̫�����������������ʶ���Ϳ������ˣ��ϻ�����˵�����ǿ�ʼ����ĵ�һ�Σ�

��ƪ���Ľ������¼���������н���
- ɶ��Html���룿
- ��ô��Html�����ж�λ����Ҫ�Ķ�����
- BeautifulSoup����
- ��������������
ɶ��Html����

��ν��html���룬������͵�������һ��������ϣ��õģ���������������һ��������������Ҽ����ҵ����鿴��ҳԴ���롱����ͬ������������������̫һ����������Chrome���������̫�࣬�ǲ����п��������������ͼ��һ�Ѳ�֪����ʲô���Ĵ��룿

����ȥ�ͺܶ��Ķ԰�

��ʵ������԰������ϵ�F12�����Ҽ�ѡ�񡰼��Ԫ�ء�����ͬ�������ͬ������ʱ����������Ҳࣨ�������360����������������·�������һ�����������������ɫ���е�����
����дͼƬ����

����������Ǹղ����ǿ����Ǹ���֪����ʲô���Ķ�������״�ṹ������ȥ������һЩ�������html���룬html������ʵ�����������"<Y yy='aaa'>xxxx</Y>"�ǵĽṹ����Ҫ�����ҳ���ϵ����ݰ���������һ�����ԡ���һ��С�ڽ���ϸ��������ṹ���ܶ���֮�����������������Ķ����󲿷ֶ�������html���룬html��������ü���˵���ǳ���Ա��һ��html���룬����Ҫչʾ����Ϣ����ָ����λ���ϵ�һ�ֶ���������html���룬����������ǰҳ���ϵĺܶ�Ԫ�أ���Ȼ������������ʽ����Ԫ��չʾ��ҳ���ϣ���css��js����Ⱦ��ʽ����Щ������һƪ����ܡ�

֪����������Ҫ����Ϣλ��html�У���ôֻ��Ҫ�ҵ�������Ҫ�ľ������������Ȼ�������������ʹ󹦸���ˣ��߼�������ô���߼������Ծ�̬����Ĺؼ�������Ҫ׼ȷ�Ľ���html���룬һ��ʹ��BeautifulSoup���������������ʽ��
��ô��Html�����ж�λ����Ҫ�Ķ���
��ǩ

��һ�����ᵽ��html�����ж���"<Y yy='aaa'>xxxx</Y>"�ṹ��һ�ԡ�<>�����ǳ�֮Ϊ��ǩ����Ա�ǩ��ͨ������һЩ���ݣ�������һ�����֣�һ���ַ�����һ����ҳ���ӣ�����һ��ͼƬ���ӵȵȣ���֮��������������ҳ�Ͽ��������ݡ���Y����֮Ϊ��ǩ������yy��Ϊ������������aaa����������ֵ����xxxx���������ǩ�����ݣ�Ҳ���Ƕ�Ӧ��ҳ���ϵ���Ϣ��һ�����������Ҫ��ȡ�ľ��ǡ�xxxx������ʱ���ǿ���Ҳ��Ҫ��ȡ��ǩ������ֵ��aaa������ǩ������Ψһ�ģ�Ҳ���������ظ��ģ��ؿ��ղ�������״�ı�ǩ�ṹ����һ�ַ����Ĳ�θУ�ͬһ��ı�ǩ���ǳ����ǻ�Ϊ�ֵܱ�ǩ����һ����ǩ�Ͱ������ı�ǩ��Ϊ���ӱ�ǩ�����a����b��b����c��d����c��a�ĺ����ǩ����b���ӱ�ǩ����d���ֵܱ�ǩ�������������ν�ģ��˽�һ�¾ͺã�һ���ǩ�����ܻ��ظ�������ǩ��������yy��������ֵ��aaa�������ظ��������ֵܱ�ǩ֮����ܻ���ֱ�ǩ����������������ֵ��ȫ��ͬ��������������ܣ�����find������findAll���������𣩡�

�ã���ʵ������һ����ַ�ѣ�http://newcar.xcar.com.cn/257/review/0.htm���ǰ��������б��ǵ�F3�Ŀڱ�ҳ�棬����Ҽ�ѡ�񡰼��Ԫ�ء�����֮�䰴�����ϵ�F12��ѡ���Ǹ����İ�ť����ɫ��1����Ȼ�����ŵ����ۿ򸽽�����ɫ��2��������ͼ��ʾ���������Ԫ�ؽ�������һ�δ��뱳��ɫ�������ɫ�����ɫ��3��

����дͼƬ����

ÿ��ҳ����10���ڱ����ɼ���10���ڱ����洢��������Ϊ��class��,����ֵΪ��review_comments_dl���ġ�div����ǩ�У���Ȼ�������ǩ����һ����Ҷ�ڵ㡱��Ҳ����˵�����ǩ�ڲ�����������ǩ�����ǽ�һ���������������ͼƬ��

����дͼƬ����

���ǿ��Կ������3���кܶ���ͬ�ı�ǩ<dl>...</dl>,���Ƕ���������Ϊ��class��,����ֵΪ��review_comments_dl���ġ�div����ǩ���ӱ�ǩ������֮�以Ϊ�ֵܱ�ǩ�����ǰ������ں��3��λ�ò�ѡ�У���ʱ�����ҳ�ĵ�һ���ڱ���λ�þͻ�����ɫ������Ҳ����˵�����3�����ǩʵ���϶�Ӧ�ź��2��������е����ݣ���ô���ǰѺ��3�پ���Ŀ�һ��������ͼ��ʾ��

���Կ�������һ���ڱ�������е����ݣ��ڵ�һ����dl����ǩ�У���ɫ�»���2����ͬ�����Կ����ڶ����ڱ��ڵڶ�����dl����ǩ�С��������������dl����ǩ�����������ӱ�ǩ����dt���͡�dd���ӱ�ǩ���ڱ�����λ��dd�ӱ�ǩ�£��õģ���������dd����ǩ������dd����ǩչ��������ͼ��ʾ��

����дͼƬ����

���3�Ǹó��ĵ�һҳ�ĵ�һ���ڱ���λ��dd��ǩ�У���ͼ����ɫ�»���<dd>...</dd> �е����ݣ�ͼ�дӿ�ͷ��ddָ����3����ע�ˡ�ͬ��������˼�Ǻ��3��������dd��ǩ�����ݣ���dd��ǩ�»����ӱ�ǩ����������Ϊclass������ֵΪuseful��div��ǩ�����������1034���ж����˾�������ڱ����ã�����һ���ӱ�ǩp��p��ǩ�������ǿڱ������ߣ�p����һ���ӱ�ǩa��a��ǩ��������������Դ����ͼ�еġ����ǵ�F3��̳����

���ˣ�������ض����Ѿ���ͨ����ǩ��λ��Ϣ�����˽��ˣ�����������ϰһ�£����ǽ��ڱ�ҳ�л�����2ҳ�����Կ�����ַ�����http://newcar.xcar.com.cn/257/review/0/0_2.htm������һ����0_2��������0_2���ĳɡ�0_1���������˵�һҳ��ʵ���ϵ�һҳ����ʵurl��http://newcar.xcar.com.cn/257/review/0/0_1.htm�������ĳɡ�0_3���͵��˵���ҳ����ô����Ӧ����ô��ȡ�ó��͵Ŀڱ�һ���м�ҳ�أ��������ͼ��

����дͼƬ����

��Ȼ���ڿ����߹����ӽǣ�����F12�����Ĵ�������ӽǣ�����������βҳ��������122�����ߡ���һҳ���ϣ��Ҳ�Ŀ��л������ͼ��ʾ�Ļ��棬���Կ���βҳ122���ڵ�λ������Ϊclass������ֵΪ��pagers����div��ǩ�ĵ����ڶ����ӱ�ǩ�У�����1��ʾ��������һҳ����λ������Ϊclass������ֵΪ��pagers����div��ǩ�����һ���ӱ�ǩ�У�����2��ʾ������ϸ�᳹һ�»ᷢ������Ϊclass������ֵΪ��pagers����div��ǩ������֮ǰѰ�ҿڱ��ı�ǩdl���ֵܱ�ǩ��λ��ȫ����dl��ǩ���ٺ���һ����Ҳ����˵���ñ�ǩ�ĸ���ǩ��dl��ǩ��ͬ����������Ϊ��class��,����ֵΪ��review_comments_dl���ġ�div����ǩ��

ΪʲôҪȷ��βҳ�أ���Ϊ�������ʱ������Ҫ֪���������ֹλ�ã�ʹ��forѭ�����õĿ��ƴ���Ŀ�ʼ����ᡣ

���������߼��������ģ��ҵ�Ŀ��ĳ��ͣ�����url��ʵ���ϣ���ͬ���͵�urlֻ��id��ͬ��������ǵ�F3��url��http://newcar.xcar.com.cn/257/���䳵��id��257����id����Ϊ258ʱ�����;ͱ���˱��ǵ�F0��Ȼ��鿴html���룬��ȷҪ��ȡ�����ݵ�����λ�ã���ȷ��ҳ���ɣ���ȷ�������ֹλ�ã���ȡβҳ��Ϣ��htmlλ�ã���Ȼ������롣
BeautifulSoup����

Pythonһ����������bs4����һ��BeautifulSoup�⣬�����ڽ���html����ģ����仰˵���ǿ��԰�����������ͨ����ǩ��λ����Ҫ����Ϣ������ֻ���������ȽϹؼ��ķ�����

1��find������findAll������
���ȣ�BeautifulSoup���Ƚ�����html��������ָ����html������һ��BeautifulSoup�����ʵ�������������ʵ����Ҫ������ֻҪ����������һ����ʹ��F12����������html�������ͺã������ʵ������ʹ�úܶ෽������õľ���find��findAll�����ߵĹ�������ͬ�ģ�ͨ��find( )�Ĳ�������find( )������ָ���ı�ǩ����������������ֵȥ������Ӧ�ı�ǩ������ȡ��������findֻ��ȡ�������ĵ�һ����ǩ����findAll�����ȡ�����������з��������ı�ǩ������һ����������ʵ�����ǽ����з��������ı�ǩ����һ��list����findAll�������ֵܱ�ǩ�Ķ�λ����ղŶ�λ�ڱ���Ϣ���ڱ�����dl��ǩ�£���ͬһҳ��10���ڱ���Ӧ��10��dl��ǩ����ʱ����find����ֻ�ܻ�ȡ��һ������findAll���ȡȫ����10����ǩ������һ���б�����Ҫ��ȡÿ����ǩ�����ݣ�ֻ�������б�ʹ��һ��forѭ������һ�鼴�ɡ�

2��get_text()������
ʹ��find��ȡ�����ݲ�������������Ҫ�����ݣ����Ұ�����ǩ����������������ֵ�ȣ�����ʹ��find������ȡ"<Y yy='aaa'>xxxx</Y>" ������xxxx��ʹ��find�����ǻ�õ�����"<Y yy='aaa'>xxxx</Y>"��ʮ���߳���ʵ��������Ҫ�Ľ����������ǩ������xxxx����ˣ���ʹ��find������Ķ�����ʹ��get_text( )�������Ϳ��Եõ���ǩ�������ˣ���Ӧ���������ͨ��get_text( )�����Ϳ��Եõ�xxxx�ˡ�

���ˣ��̵����Ĳ���ˣ��ϴ��뿩~~~
��������������

ʹ��Python3����Ҫ��ǰ��װbs4�⣬�����Ļ�����win7+Python3+Pycharm����ʱ��Ҳ��Ubuntu16.04+Python3+Pycharm�����ܶ�ʱ�������ʲ�����ʲôide�����أ�jupyter notebook��spyder��Pycharm������ֻ�ܺʹ��˵����ide����ǧ������̣������棩ʹ��pycharm�϶�����ѡ�����ֻ��ƽʱ����ϰ��д��С����ʹ��jupyter notebook��spyder�Ͳ�������֮������漰��Ƶ����ӡ�������Ķ�������û�����pycharm����Ҫ��jupyter notebook����Ȼ��ܿ���

�Թ��������ϴ��룡

����˵������������У�html���뾭������֡�class���������������class��python�С��ࡱ�Ĺؼ��֣��������find�����������������ԣ��ǲ���Ҫ�����ŵģ����ֱ������class�ǻ��������ģ�������Ҫע�⣬ÿ������classʱӦ������Ϊclass_����class���һ���»��ߣ�

�ڶ������·�����һ��ʼ��һ��add_header�Ĺ��̣�Ϊ���ǽ�����αװ����������ܶ���վ�Ƿ���������������Ϣ������ȡ�ģ����Ի��ֹһЩ����������ǵ���վ��ͨ��add_header������������αװ�����������������վ�������������ľͲ���һ�����򣬶���һ�������������˵��һ�������û��ˡ�

import urllib
import urllib.request
from bs4 import BeautifulSoup
import re
import random
import time

# ����Ŀ��url��ʹ��urllib.request.Request��������
url0 = "http://newcar.xcar.com.cn/257/review/0.htm"
req0 = urllib.request.Request(url0)

# ʹ��add_header��������ͷ��������αװ�������
req0.add_header("User-Agent","Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/59.0.3071.115 Safari/537.36")

# ʹ��urllib.request.urlopen��ҳ�棬ʹ��read��������html����
html0 = urllib.request.urlopen(req0).read()

# ʹ��BeautifulSoup����html�����BeautifulSoupʵ������Ϊsoup0
soup0 = BeautifulSoup(html0)

# ��ȡβҳ������ǰһС�ڻ�ȡβҳ�����ݿ���������ˣ�
total_page = int(soup0.find("div",class_= "pagers").findAll("a")[-2].get_text())
myfile = open("aika_qc_gn_1_1_1.txt","a")
print("user","��Դ","��Ϊ��������","����","����ʱ��","comment",sep="|",file=myfile)
for i in list(range(1,total_page+1)):
    # ���������ͣʱ��
    stop = random.uniform(1, 3)
    url = "http://newcar.xcar.com.cn/257/review/0/0_" + str(i) + ".htm"
    req = urllib.request.Request(url)
    req.add_header("User-Agent","Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/59.0.3071.115 Safari/537.36")
    html = urllib.request.urlopen(req).read()
    soup = BeautifulSoup(html)
    contents = soup.find('div', class_="review_comments").findAll("dl")
    l = len(contents)
    for content in contents:
        tiaoshu = contents.index(content)
        try:
            ss = "������ȡ��%dҳ�ĵ�%d�����ۣ���ַΪ%s" % (i, tiaoshu + 1, url)
            print(ss)
            try:
                comment_jiaodu = content.find("dt").find("em").find("a").get_text().strip().replace("\n","").replace("\t","").replace("\r","")
            except:
                comment_jiaodu = ""
            try:
                comment_type0 = content.find("dt").get_text().strip().replace("\n","").replace("\t","").replace("\r","")
                comment_type1 = comment_type0.split("��")[1]
                comment_type = comment_type1.split("��")[0]
            except:
                comment_type = "����"
            # ��Ϊ�����������õ�����
            try:
                useful = int(content.find("dd").find("div",class_ = "useful").find("i").find("span").get_text().strip().replace("\n","").replace("\t","").replace("\r",""))
            except:
                useful = ""
            # ������Դ
            try:
                comment_region = content.find("dd").find("p").find("a").get_text().strip().replace("\n","").replace("\t","").replace("\r","")
            except:
                comment_region = ""
            # ����������
            try:
                user = content.find("dd").find("p").get_text().strip().replace("\n","").replace("\t","").replace("\r","").split("��")[-1]
            except:
                user = ""
            # ��������
            try:
                comment_url = content.find('dt').findAll('a')[-1]['href']
                urlc = comment_url
                reqc = urllib.request.Request(urlc)
                reqc.add_header("User-Agent",
                                "Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/59.0.3071.115 Safari/537.36")
                htmlc = urllib.request.urlopen(reqc).read()
                soupc = BeautifulSoup(htmlc)
                comment0 = \
                soupc.find('div', id='mainNew').find('div', class_='maintable').findAll('form')[1].find('table',class_='t_msg').findAll('tr')[1]
                try:
                    comment = comment0.find('font').get_text().strip().replace("\n", "").replace("\t", "")
                except:
                    comment = ""
                try:
                    comment_time = soupc.find('div', id='mainNew').find('div', class_='maintable').findAll('form')[1].find('table', class_='t_msg').\
                    find('div', style='padding-top: 4px;float:left').get_text().strip().replace("\n","").replace( "\t", "")[4:]
                except:
                    comment_time = ""
            except:
                try:
                    comment = content.find("dd").get_text().split("\n")[-1].split('\r')[-1].strip().replace("\n", "").replace("\t","").replace("\r", "").split("��")[-1]
                except:
                    comment = ""
            # time.sleep(stop)
            print(user,comment_region,useful,comment_type,comment_time,comment, sep="|", file=myfile)
        except:
            s = "��ȡ��%dҳ�ĵ�%d������ʧ�ܣ���ַΪ%s" % (i, tiaoshu + 1, url)
            print(s)
            pass
myfile.close()

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    11
    12
    13
    14
    15
    16
    17
    18
    19
    20
    21
    22
    23
    24
    25
    26
    27
    28
    29
    30
    31
    32
    33
    34
    35
    36
    37
    38
    39
    40
    41
    42
    43
    44
    45
    46
    47
    48
    49
    50
    51
    52
    53
    54
    55
    56
    57
    58
    59
    60
    61
    62
    63
    64
    65
    66
    67
    68
    69
    70
    71
    72
    73
    74
    75
    76
    77
    78
    79
    80
    81
    82
    83
    84
    85
    86
    87
    88
    89
    90
    91
    92
    93
    94
    95
    96

����˵��һ�£�try����except����ṹ���������е���if����else�Ľṹ����һ���ǳ���Ҫ�Ĺ��̣�Ϊ��ʹ�������������õ����У������ڸտ�ʼ�������Ӿͱ������ֶ����˵��������Ҫ�ܺõ�����try����except���̡��������ִ��try�µ���䣬�������ʧ�ܣ��ͻ�ִ��except�µ���䣬��Ҳ����ʹ�ö��try����exceptǶ�׵Ľṹ��ɸ��ӵ�����ĸ��ǣ����Ҫ��֤���try����except���̰����˳���������������������ô��Ĵ���������������ġ�

���������һ������γ�Ҳ�͵������ˣ�����֮�����ܶ�̬���棬���֮����ʱ�䣬�������һ��selenium���ģ������Ŀ⣬�Լ������ܻ��з������֪ʶ�����Լ������棬��������ɣ�����Ҳ�����һЩ����word2vec��fastText�ı������㷨�����ݣ�������ʲô�����뽻���Ŀ�������~��Ҳ�Ǹ�����ѧϰ·�ϵ��У�ϣ���ܺ͸�·�����Լ���ţ������
Ŀ¼

    Python����д��Ư�����������1
        ɶ��Html����
        ��ô��Html�����ж�λ����Ҫ�Ķ���
            ��ǩ
        BeautifulSoup����
        ������������
            Ŀ¼
