# DownUnder CTF 2020 Taking-stock

## 题目详情

- DownUnder CTF 2020 Taking-stock
- After taking one unit of AI at uni I'm now a pro. My linear regression model is amazing at predicting the stock market. I'm so proud of it I'm even offering it as a service. Can't wait to get that VC money!

## 考点

- LFI
- pickle deserialization
- Upload

## 启动

    docker-compose up -d
    open http://127.0.0.1:4534/

### Writeups

- [writeup.md](https://tiaonmmn.github.io/2020/09/22/DownunderCTF-Web-Taking-stock/)

## 复现说明及修改

- 该环境根据[DownUnderCTF官方Repo](https://github.com/DownUnderCTF/Challenges_2020_public/tree/master/web/cookie-clicker)源码进行复现。
- flag位于容器内：/flag_aR4EfMH98EsNz1mg0bSITg，容器外：meta/flag。
- 本题部署时需要给出publish文件夹下的train.py

## 版权

该题目复现环境尚未取得主办方及出题人相关授权，如果侵权，请联系本人删除（ tiaonmmn@live.cn ）
