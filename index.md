---
layout: page
title: $100 달러 오픈 슈퍼 컴퓨터
---

[xwMOOC](http://www.xwmooc.net/)에서 개발하고 있는 $100 달러 오픈 슈퍼 컴퓨터입니다. 

> ## 준비물 {.getready}
>
> [라즈베리 파이 컴퓨터](http://raspberrypi.org/)
>

### 고성능 컴퓨팅[^1] 개발

1. [슈퍼 컴퓨터 하드웨어](rpi-super-computer.html) [^xwMOOC-intern]
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
1. 고성능 컴퓨팅 기초
    - [숫자 (Numbers)](basic-numbers.html)
    - [원격 작업 (Working Remotely)](basic-ssh.html)
1. 클라우드 OS 
    - [오픈스택(OpenStack)](openstack.html): 프로그래밍 가능한 IT 인프라
    - [클라우드 파운드리-블루믹스](bluemix.html)    


### 고성능 컴퓨팅 참고 문헌

#### 파이썬 교재
- [Parallel Programming with Python 2014](http://www.amazon.com/Parallel-Programming-Python-Jan-Palach/dp/1783288396)
- [Python High Performance Programming 2013](http://www.amazon.com/Python-Performance-Programming-Gabriele-Lanaro/dp/1783288450)
- [Mastering Python High Performance 2015](http://www.amazon.com/Mastering-Python-Performance-Fernando-Doglio/dp/1783989300)
- [A Primer on Scientiﬁc Programming with Python](http://www.springer.com/us/book/9783642302930)

#### 파이썬 논문
- L. Dalcin, P. Kler, R. Paz, and A. Cosimo, Parallel Distributed Computing using Python, Advances in Water Resources, 34(9):1124-1139, 2011. [http://dx.doi.org/10.1016/j.advwatres.2011.04.013](http://dx.doi.org/10.1016/j.advwatres.2011.04.013)


> ## 참고 자료 {.prereq}
> - [컴퓨터 과학 언플러그드](http://unplugged.xwmooc.org)  
> - [리보그](http://reeborg.xwmooc.org)  
>      - [러플](http://rur-ple.xwmooc.org)  
> - [파이썬 거북이](http://swcarpentry.github.io/python-novice-turtles/index-kr.html)  
> - [정보과학을 위한 파이썬](http://python.xwmooc.org)  
> - [소프트웨어 카펜트리 5.3](http://statkclee.github.io/swcarpentry-version-5-3-new/)
>     - [소프트웨어 카펜트리 5.2](http://swcarpentry.xwmooc.org)
> - [R 팩키지](http://r-pkgs.xwmooc.org/)
> - [통계적 사고](http://think-stat.xwmooc.org/)
> - [$100 오픈 컴퓨터](http://computer.xwmooc.org/)
>     - [IoT 라즈베리파이](http://raspberry-pi.xwmooc.org/)

[^xwMOOC-intern]: [xwMOOC 개인용슈퍼컴퓨터 개발 프로젝트 - xwMOOC 인턴(서상범)](http://www.landmarkonme.com/)
[^1]: [고성능 컴퓨팅, High-Performance Computing](https://ko.wikipedia.org/wiki/고성능_컴퓨팅)은 고급 연산 문제를 풀기 위하여 슈퍼컴퓨터 및 컴퓨터 클러스터를 사용하는 것을 말한다.

