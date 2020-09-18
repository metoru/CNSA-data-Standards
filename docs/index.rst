.. 文档编排 documentation master file, created by
   sphinx-quickstart on Sat Dec 02 14:24:43 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.




CNSA 数据标准
===========


概述
-------

::

	下载文档

数据标准文档：

* 变异数据标准
* 提交人数据标准
* - `样本数据标准 <https://github.com/metoru/CNSA-data-Standards/blob/master/%E5%8E%9F%E5%A7%8B%E6%95%B0%E6%8D%AE%E6%A0%87%E5%87%86-zl.xlsx>`_
* 
* ...



| 字段名                   | 缩写          | 字段描述                                        | 字段类型 | 是否必填 | 是否唯一性字段 | 取值范围 | 示例 | 注解 |
| --------------------------- | --------------- | --------------------------------------------------- | -------- | -------- | -------------- | -------- | ---- | ---- |
| First name                  | first_name      | First (given) name of the submitter.                | varchar  | 必填   | 否            | 128      | wang |      |
| Middle name                 | middle_name     | Middle name of the submitter.                       | varchar  | 选填   | 否            | 128      |      |      |
| Last name                   | last_name       | Last (family) name of the submitter.                | varchar  | 必填   | 否            | 128      |      |      |
| Primary E-mail              | email_primary   | Primary Email address of the submitter.             | varchar  | 必填   | 否            | 128      |      |      |
| Secondary E-mail            | email_secondary | Secondary/Alternate Email address of the submitter. | varchar  | 选填   | 否            | 128      |      |      |
| Submitting organization     | organization    | Full name of submitter’s organization.            | varchar  | 必填   | 否            | 128      |      |      |
| Submitting organization URL | org_url         | The URL of submitter’s organization.              | varchar  | 选填   | 否            | 128      |      |      |
| Department                  | department      | The department of the submitter.                    | varchar  | 必填   | 否            | 128      |      |      |
| Phone                       | phone           | The phone number of the submitter.                  | varchar  | 选填   | 否            | 128      |      |      |
| Fax                         | fax             | The Fax number of the submitter.                    | varchar  | 选填   | 否            | 128      |      |      |
| Street                      | street          | The street name of the submitter.                   | varchar  | 必填   | 否            | 256      |      |      |
| City                        | city            | The city name of the submitter.                     | varchar  | 必填   | 否            | 128      |      |      |
| Postal code                 | postal_code     | The Postal code of the submitter.                   | varchar  | 选填   | 否            | 128      |      |      |
| State/Province              | state_province  | The state/province of the submitter.                | varchar  | 选填   | 否            | 64       |      |      |
| Country                     | country         | The Country/Region of the submitter.                | varchar  | 必填   | 否            | 64       |      |      |


目录
------

.. toctree::
   :titlesonly:
   :glob:

   sphinx/index
   gitbook/index




........................\ *持续更新中*\ ......................





