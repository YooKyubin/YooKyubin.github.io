---
layout: post
title: 교점의 좌표 구하기
subtitle: 두 직선의 계수로 나타내는 교점의 좌표
gh-repo: daattali/beautiful-jekyll
comments: true
---


# 교점의 좌표 구하기
직선 $ax + by + e = 0$ 와, 직선 $cx + dy + f = 0$에 대하여 
두 직선의 교점의 좌표를 구한다.

$$
ax + by + e = cx + dy + f
$$
식 전체를 a로 나누기
$$
x + \frac{b}{a}y + \frac{e}{a}  = \frac{c}{a}x + \frac{d}{a}y + \frac{f}{a}
$$
$x$에 대한 식으로 표현
$$
x(\frac{a-c}{a}) = y(\frac{d-b}{a}) + \frac{f-e}{a} 
$$

$$
x = y(\frac{d-b}{a-c}) + \frac{f-e}{a-c}
$$
수식 $ax + by + e=0$ 이나, $cx + dy + f=0$ 에 $x = y(\frac{d-b}{a-c}) + \frac{f-e}{a-c}$대입
$$
a(y(\frac{d-b}{a-c}) + \frac{f-e}{a-c}) + by + e = 0
$$

$$
= y\frac{ad-ab}{a-c} + \frac{af-ae}{a-c} + y\frac{ba-bc}{a-c} + \frac{ae-ce}{a-c} = 0
$$

$$
= y\frac{ad-ab+ab-bc}{a-c} + \frac{af-ae+ae-ce}{a-c} = 0
$$
양 변에 $a-c$를 곱하면
$$
y(ad-bc) + (af-ce) = 0
$$

$$
y=\frac{ce-af}{ad-bc}
$$

$y$를 수식 $ax + by + e=0$에 다시 대입하면
$$
ax + b\frac{ce-af}{ad-bc} + e=0
$$

$$
x\frac{aad-abc}{ad-bc} + \frac{bce-abf}{ad-bc} + \frac{ade-bce}{ad-bc} = 0
$$

$$
x\frac{aad-abc}{ad-bc} + \frac{ade-abf}{ad-bc} = 0
$$
x에 대한 식으로 작성한 뒤 양 변에 $a$를 나누어 주면
$$
x\frac{ad-bc}{ad-bc} = \frac{bf-de}{ad-bc} 
$$

$$
x = \frac{bf-de}{ad-bc}
$$
따라서 교점의 좌표는
$$
x = \frac{bf-de}{ad-bc}, y=\frac{ce-af}{ad-bc}
$$
