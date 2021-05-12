# Jesse_project_01

- SQL version 1.0 -

#基本說明:
簡易新建一個資料庫，後續將會進行CRUD的修改，並練習版本控管的方式

#附加檔案:
Demo用的SQL檔

#作業系統
win10


- SQL version 2.0 -

#基本說明:
新增數個資料進去資料庫，並進行刪除與修改的動作，並試著做版本控管

#附加檔案
Demo用的SQL檔

#作業系統
Win10


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


- SSMS_for_PostgreSQL_import -

#基本說明:
將 SSMS 將資料透過 PostgreSql ODBC 匯出到 PostgreSQL <br>
參考來源:https://rainmakerho.github.io/2021/02/04/Migrate-MS-SQL-to-PostgreSQL-1/

#突發狀況:<br>
-左圖為將資料全部選取匯入畫面<br>
-右圖為送出時跑出的警示畫面，語法不同所導致<br>
<以至於輸出後無法匯出完整的資料庫><br>
<div align="center">
	<img src="https://github.com/YiWeiChennn/Jesse_project_01/blob/main/1620723551223.jpg" alt="Editor" width="500" height="600">
	<img src="https://github.com/YiWeiChennn/Jesse_project_01/blob/main/1620723570429.jpg" alt="Editor" width="500" height="600">
</div>

#資料庫內容:
總共:298筆<br>
匯入正常:206筆(資料庫目前數量)<br>
匯入不完全:39筆(由於資料內容不完整，已先剔除)<br>
匯入失敗:53筆<br>

- 匯入不正常:
1.  assessformlist
2.  assessformlistuser
3.  assessformlistuseraudit
4.  assessformprojcustomizelist
5.  assessformprojectlistuseraudit
6.  assessformprojleaderlist
7.  assessformprojeleaderlistuseraudit
8.  assessformprojleaderlistuser
9.  customercontact
10. dgauthtype
11. employeeinfopay
12. exptdocs
13. exptflow
14. fishtankinfo
15. giftapplicaationlist
16. pcmtf
17. pcmtg
18. pdmbommixtem
19. projectinfofiles
20. projectinfostarttemplate
21. projectinfotasklog
22. projectmeetingnotes
23. projectnoteaudit
24. projectnotefiles
25. projecttempletask
26. syscalendardate
27. syscategory
28. syscode
29. syscontent
30. syscontenttype
31. sysflowbasenode
32. sysflownode
33. sysforumdetail
34. sysgroup
35. sysimage
36. syskmsharetype
37. sysrole
38. systype
39. usertodo

- 匯入失敗:
1.  custsrvcontactlisttask
2.  custsrvdailyreport
3.  custsrvdailyreportback
4.  device
5.  devicecation
6.  corppaytaxlist
7.  corpprojecthwcost
8.  corptripform
9.  corptripformitem
10.  custds3070
11. custrepairorder
12. custrepairorderitem
13. custsrvcalendar
14. custsrvcontactlist
15. custsrvcontactlistandit
16. employeeinfo
17. employeeinfopunch
18. foodcorpinfoorder
19. hrforgotpunch
20. hrforgotpunchitem
21. hrovertimeappdform
22. hrovertimeappdformitem
23. hrovertimeform
24. hrovertimeformitem
25. hrvoteinfo
26. internalcontactlist
27. internalcontactlistandit
28. internalcontactlistitem
29. internalcontactlisttask
30. materialsinfo
31. openissuefiles
32. openwkinfo
33. pdmbominfo
34. pdmbomprecost
35. projectinfo
36. projectinfostart
37. projectinfostartback
38. projectinfotask
39. projectinfoweeklyreport
40. projectinfoweeklyreportnote
41. projectmeeting
42. projectmorequest
43. projectnote
44. projectnoteback
45. projectrequest
46. projectrequestaudit
47. projectrequestcontactlist
48. projectrequeststartother
49. projectrequeststtask
50. purcgasinfo
51. quotationapplyitem
52. sysyser
53. vmapplylist


#附加檔案:
MacHTA.sql

#作業系統:
Windows server 2012
