
#       ProxyLogon
        
##       何謂ProxyLogon  
ProxyLogon為重大的「無需驗證的遠端程式碼執行（Pre-Auth Remote Code Execution， Pre-Auth RCE）零日漏洞，讓攻擊者得以繞過身份驗證步驟，驅使系統管理員協助執行惡意文件或執行指令，進而觸發更廣泛的攻擊。

##       危害
ProxyLogon漏洞已經各種駭客組織，對多個產業進行無差別攻擊，企圖竊取資訊。被發現的攻擊程式包括植入web shell、採礦軟體、以及最新揭露的DearCry及Black Kingdom勒索軟體等等。
安全廠商ESET也發現，至少有10個APT駭客組織企圖染指未修補的Exchange Server。


##       觀點     
由於可以繞過身分驗證，直接使用系統管理員的權限，駭客可以得到高機密資料，這樣的資料外洩會造成公司很大的危害，且有可能遭到惡意竄改資料、破壞server等疑慮。








參考資料
https://netmag.tw/2021/03/26/%E5%BE%AE%E8%BB%9F%EF%BC%9A%E5%85%A8%E7%90%8392%E7%9A%84exchange-server%E5%B7%B2%E7%B6%93%E5%AE%89%E5%85%A8%E4%BA%86
https://technews.tw/2021/03/10/microsoft-exchange-server-devcore/
