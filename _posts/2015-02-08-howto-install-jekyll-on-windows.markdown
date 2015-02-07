---
layout: post
title: "Howto Install Jekyll On Windows"
date:   2015-02-08 03:00:25
categories: howto
tags: featured
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
---
#시작하기 전
> 친절한 가이드와 달리 설치과정에서 수많은 에러를 만나게 된다.. 당황하지 말고 설치를 성공해보자. 

#파일 다운로드
http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.1.5.exe?direct
http://cdn.rubyinstaller.org/archives/devkits/DevKit-mingw64-32-4.7.2-20130224-1151-sfx.exe

#Ruby 및 DevTools 설치


#Jekyll 설치
gem install jekyll 

위 명령어를 실행하면 ssl 검증을 할 수 없다는 에러 메시지가 출력된다. 

이럴 경우 gem 의 소스 url을 HTTP 주소로 바꿔주면 된다. 

gem source -r https://rubygems.org
gem source -a http://rubygems.org

#Header1
##Header2

#Blockquotes
>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus

#Lists
##orderd lists
1. one
2. two
3. three

##unorderd lists
- Apple
- Banana
- Plum

#Links
This is an [example link](http://example.com/ "With a Title").

#Combinations
>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus
>
> - Apple
> - Banana
> - Plum
