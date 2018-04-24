---
layout: page
title: 고성능 컴퓨팅(HPC)
---


1. [고성능 컴퓨팅 기초](hpc-basic.html)
    - [숫자 (Numbers)](basic-numbers.html)
    - [원격 작업 (Working Remotely)](basic-ssh.html)
    - [자유 소프트웨어와 오픈 소스 소프트웨어에 대한 철학](http://statkclee.github.io/open-source-for-business/ch01-philosophy.html)
    - [컴퓨터 소프트웨어 과외](http://statkclee.github.io/open-source-for-business/ch02-tutorial-on-computer-software.html)
    - [컴파일, 설치, 호출](compile-install-call.html)
1. 클라우드 OS 
    - [오픈스택(OpenStack)](openstack.html): 프로그래밍 가능한 IT 인프라
    - [클라우드 파운드리-블루믹스](bluemix.html)    
1. [고성능 컴퓨팅 개발](rpi-super-computer.html) [^xwMOOC-intern] [^1] 
    - [RPi 슈퍼 컴퓨터 자재명세서](rpi-super-bom.html)
    - [라즈베리파이 클러스터(병렬연결) - 제작매뉴얼](rpi-manual.html)
        + MPI 프로그램을 통해 모든 라즈베리파이를 하나로 병렬연결한다.
    - [네트워크 관계없이 외부에서 라즈베리파이 접속하기](rpi-network.html)
        + 내부 ip 설정 및 고정 ip 지정
        + weaved : 외부에서 포트를 통한 라즈베리파이 접속 프로그램
    - [성능시험1 - 간단한 파이썬 코드](rpi-benchmark-simple.html)
        + 간단한 파이썬 코드를 통해 병렬컴퓨팅 작업을 테스트한다.
    - [성능시험2 - HPL을 통한 객관적 성능](rpi-benchmark-hpl.html)
        + HPL(High Performance Linpack)을 통해 제작한 슈퍼컴퓨터의 성능을 객관적으로 출력하여 비교한다.
    - [tcp socket을 통한 실시간 연결상태 체크](rpi-monitoring.html)
        + 많은 라즈베리파이의 실시간 관리를 가능하게 한다.


# 고성능 컴퓨팅 참고 문헌

## 파이썬 교재
- [Parallel Programming with Python 2014](http://www.amazon.com/Parallel-Programming-Python-Jan-Palach/dp/1783288396)
- [Python High Performance Programming 2013](http://www.amazon.com/Python-Performance-Programming-Gabriele-Lanaro/dp/1783288450)
- [Mastering Python High Performance 2015](http://www.amazon.com/Mastering-Python-Performance-Fernando-Doglio/dp/1783989300)
- [A Primer on Scientiﬁc Programming with Python](http://www.springer.com/us/book/9783642302930)

## 파이썬 논문
- L. Dalcin, P. Kler, R. Paz, and A. Cosimo, Parallel Distributed Computing using Python, Advances in Water Resources, 34(9):1124-1139, 2011. [http://dx.doi.org/10.1016/j.advwatres.2011.04.013](http://dx.doi.org/10.1016/j.advwatres.2011.04.013)

### [xwMOOC 오픈 교재](https://statkclee.github.io/xwMOOC/)

- **컴퓨팅 사고력(Computational Thinking)**
    - [컴퓨터 과학 언플러그드](http://statkclee.github.io/unplugged)  
    - [리보그 - 프로그래밍과 문제해결](https://statkclee.github.io/code-perspectives/)  
         - [러플](http://statkclee.github.io/rur-ple/)  
    - [파이썬 거북이](http://swcarpentry.github.io/python-novice-turtles/index-kr.html)  
    - [정보과학을 위한 파이썬](https://statkclee.github.io/pythonlearn-kr/)  
    - [소프트웨어 카펜트리 5.3](http://statkclee.github.io/swcarpentry-version-5-3-new/)
    - [기호 수학(Symbolic Math)](https://statkclee.github.io/symbolic-math/)
    - [데이터 과학을 위한 R 알고리즘](https://statkclee.github.io/r-algorithm/)
    - [데이터 과학을 위한 저작도구](https://statkclee.github.io/ds-authoring/)
        - [The Official xwMOOC Blog](https://xwmooc.netlify.com/)
    - [비즈니스를 위한 오픈 소스 소프트웨어](http://statkclee.github.io/open-source-for-business/)
- **데이터 과학**
    - [R 데이터과학](https://statkclee.github.io/data-science/)
    - [시각화](https://statkclee.github.io/viz/)
    - [텍스트 - 자연어처리(NLP)](https://statkclee.github.io/text/)
    - [데이터 과학– 기초 통계](https://statkclee.github.io/statistics/)    
        - [공개 기초 통계학 - OpenIntro Statistics](https://statkclee.github.io/openIntro-statistics-bookdown/)
    - [데이터 제품](https://statkclee.github.io/data-product/)
    - [보안 R](https://statkclee.github.io/security/) - TBA
    - [R 도커](http://statkclee.github.io/r-docker/)
    - [공간통계를 위한 데이터 과학](https://statkclee.github.io/spatial/)
    - [~~R 팩키지~~](http://r-pkgs.xwmooc.org/)
    - [~~통계적 사고~~](http://think-stat.xwmooc.org/)
- **기계학습, 딥러닝, 인공지능**
    - [기계학습](http://statkclee.github.io/ml)
    - [딥러닝](http://statkclee.github.io/deep-learning)
    - [R 병렬 프로그래밍](http://statkclee.github.io/parallel-r/)
    - [고생대 프로젝트](http://statkclee.github.io/trilobite)
    - [인공지능 연구회](https://statkclee.github.io/ai-lab/)
- [IoT 오픈 하드웨어(라즈베리 파이)](http://statkclee.github.io/raspberry-pi)
    - [$100 오픈 컴퓨터](https://statkclee.github.io/one-page/)   
    - [$100 오픈 슈퍼컴퓨터](https://statkclee.github.io/hpc/)
- [선거와 투표](http://statkclee.github.io/politics)
    - [저녁이 있는 삶과 새판짜기 - 제7공화국](https://statkclee.github.io/hq/)



[^xwMOOC-intern]: [xwMOOC 개인용슈퍼컴퓨터 개발 프로젝트 - xwMOOC 인턴(서상범)](http://www.landmarkonme.com/)
[^1]: [고성능 컴퓨팅, High-Performance Computing](https://ko.wikipedia.org/wiki/고성능_컴퓨팅)은 고급 연산 문제를 풀기 위하여 슈퍼컴퓨터 및 컴퓨터 클러스터를 사용하는 것을 말한다.

