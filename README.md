﻿# **Python Qimendunjia Kinqimen Python 奇門遁甲 堅奇門**

簡單時家奇門及金函玉鏡奇門遁甲起盤 A simple python package of Qimendunjia in Chinese hour-based system and golden letter jade mirror style Qimendunjia for prediction.

堅奇門排盤 https://kinqimen.streamlitapp.com

[![Python](https://img.shields.io/pypi/pyversions/kinqimen)](https://pypi.org/project/kinqimen/)
[![PIP](https://img.shields.io/pypi/v/kinqimen)](https://pypi.org/project/kinqimen/)
[![Downloads](https://img.shields.io/pypi/dm/kinqimen)](https://pypi.org/project/kinqimen/)
[![TG](https://img.shields.io/badge/chat-on%20telegram-blue)](https://t.me/gnatnek)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?logo=paypal&style=flat-square)](https://www.paypal.me/kinyeah)&nbsp;

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/CADAL06056497_%E9%81%81%E7%94%B2%E6%BC%94%E7%BE%A9%C2%B7%E5%8D%B7%E4%B8%89~%E5%8D%B7%E5%9B%9B.djvu/page123-452px-CADAL06056497_%E9%81%81%E7%94%B2%E6%BC%94%E7%BE%A9%C2%B7%E5%8D%B7%E4%B8%89~%E5%8D%B7%E5%9B%9B.djvu.jpg "遁甲演義陰遁七局排盤")
![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/CADAL06056497_%E9%81%81%E7%94%B2%E6%BC%94%E7%BE%A9%C2%B7%E5%8D%B7%E4%B8%89~%E5%8D%B7%E5%9B%9B.djvu/page104-444px-CADAL06056497_%E9%81%81%E7%94%B2%E6%BC%94%E7%BE%A9%C2%B7%E5%8D%B7%E4%B8%89~%E5%8D%B7%E5%9B%9B.djvu.jpg "遁甲演義陰遁七局排盤")


## **1. 導讀 Introduction**︰
奇門遁甲與大六壬、太乙神數並稱三式。為中國神秘學中預測學的一個特有門類。乃利用洛書軌跡，九宮八卦以及五行相生相剋的道理，來預測地理方向的優劣，進而規劃一個人的行程，最終達到對自己最有利的目的，為算命相術所兼用。奇門遁甲以乙、丙、丁稱為三奇；以開、休、生、傷、杜、景、驚、死稱為八門，故名「奇門」。天干中「甲」最尊貴而不顯露，六甲(甲子、甲戌、甲申、甲午、甲辰、甲寅)常隱藏於「戊、己、庚、辛、壬、癸」六儀之內，三奇、六儀分布九宮，而甲不獨占一宮，故名「遁甲」。在古代民間流傳只有帝王附近如軍師、欽天監、國師等重要大臣才通曉奇門遁甲之術。

Qimen Dunjia is an ancient form of divination from China. It is one of the Three Styles (三式; sānshì; 'three rites') of Chinese divination, with DaLiuRen and TaiYi Shen Shu. Over the centuries of Chinese history, Qimen Dunjia grew in popularity and was expanded to include a number of other types of divination, including medical divination, matchmaking, childbirth, travel, personal fortunes, and today includes contemporary applications, most notably that of business and finance. 

Qimen Dunjia is based on astronomical observations, and consists of various aspects of Chinese metaphysics, including the doctrines of yin and yang, five elements, the eight trigrams, the ten Heavenly Stems and the twelve Earthly Branches, as well as the twenty-four solar terms. The Qimen Dunjia cosmic board consists of a 3 × 3 magic square of nine palaces (九宫), which includes a Heaven and Earth plate, a spirit plate, eight gates and a star plate. The various symbols rotate around the palaces with each double-hour of the day, making a total of 1,080 different configurations of the Qimen Dunjia cosmic board. These situations (局; jú) are recycled four times per year, and are divided between the Yin and Yang halves of the year. Qimen Dunjia is time-sensitive. The analyst makes reference to the configuration of the cosmic board at the time when a question is posed, or for birth times of individuals or corporate entities, such as businesses or nations. At times, the same or very similar configurations of the cosmic board will appear in relation to the same series of questions or problems.

## **2. 安裝套件 Installation**

```python
	pip install sxtwl
	pip install kinqimen
```

## **3. 起課方式 Quickstart**
```python
	from kinqimen import kinqimen
	kinqimen.Qimen(year, month, day, hour).pan() (時家奇門)
	kinqimenQimen(year, month, day, hour).gpan() (金函日家)
	kinqimen.Qimen(year, month, day, hour).overall() (時家奇門 + 金函日家)
	
```





