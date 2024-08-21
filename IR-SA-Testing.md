# SA vs IR testing

I wanted to run some testing on IR versus SA, as, for all intents and purposes, it should end up with SA ahead, since 50 > 40

That being said, I wouldn't be writing this if it was that simple.


## Test parameters

![image](https://github.com/user-attachments/assets/9c4d726f-809b-49b0-9d87-f03e193342a6)

Above is the difference in stats between two builds. One SA, all ATK mains, one IR, also all ATK mains.

I then proceeded to use 3 healers and laurel, and tested on NM4, to see damage results. 

And for the most part, these were reasonable, and will be in the section below.


<details>


<summary><h3>Tests ran</h3></summary> 

#### Hatssut SA

![image](https://github.com/user-attachments/assets/049f355c-8c68-483e-8f2e-fbb17362b29d)

#### Hatssut IR

![image](https://github.com/user-attachments/assets/6f3fff6d-7077-4d2a-80ee-c999a4adb8a5)


#### Valk SA

![image](https://github.com/user-attachments/assets/77865153-af50-442c-b90f-68911fe6c345)

#### Valk IR

![image](https://github.com/user-attachments/assets/6d94f65a-d70d-4ad1-a293-4e625850e246)

#### Khamet SA

![image](https://github.com/user-attachments/assets/ada3f5d3-2cd3-4b9d-83de-bfb90d1f7313)

#### Khamet IR

You get the idea.

</details>

But then I got this.

### Setram IR

![image](https://github.com/user-attachments/assets/9888cb4f-3f6e-4e0a-aaec-0e38ebf51f0f)

### Setram SA

![image](https://github.com/user-attachments/assets/0413b940-94fc-4061-be1f-1ab09b6f381c)


And so I ran the test 3 more times to be sure. And then I tested some other champions. And only setram continued to have similar results.

So there were three hypothesis to move forward with.

- CDMG somehow affected this.
- DMG % somehow affected this.
- Inferal unit, infernal roar, conspiracy confirmed :tinfoil:



So I started testing. And, for the most part, CDMG seemed to have little difference. **DMG % however, reduced the gap between the two**

<details>


<summary><h2>Khamet results</h2></summary> 


### Khamet IR with Ajax on the field

![image](https://github.com/user-attachments/assets/5ee4956d-2473-42e1-bed1-164e41543d6a)

5.98% total damage increase, which lines up with a 6% damage increase from Ajax

### Khamet SA with Ajax on the field

![image](https://github.com/user-attachments/assets/52d3f500-4cb2-4561-aa33-cb569ce1228b)

3.99% total damage increase only

### Khamet IR, Ajax on field, Morale set on field

![image](https://github.com/user-attachments/assets/7a3a6985-1c40-4a72-9957-1572dc7f3d8a)

3.78% total damage increase, again, lining up fairly reasonably with the 4% of morale

### Khamet SA, Ajax on field, Morale set on field

![image](https://github.com/user-attachments/assets/6a3ea4b8-b60b-40ee-8fe8-1ef95d27e8d3)

2.57% total damage increase. Once more, missing the mark.


And so I continued down the rabbit hole to be sure

### Khamet IR, Ajax on field, Morale set on field, tidal ring

![image](https://github.com/user-attachments/assets/d6e8c2dc-9e9f-4992-9657-c20839f9f042)

### Khamet SA, Ajax on field, Morale set on field, tidal ring

![image](https://github.com/user-attachments/assets/75f840fc-7d56-4bc2-b39a-177dc896bd35)

### Khamet IR, Ajax on field, Morale set on field, tidal ring, Orim buff

![image](https://github.com/user-attachments/assets/82c5efbd-d399-4ef6-a649-8863cc589218)

### Khamet SA, Ajax on field, Morale set on field, tidal ring, Orim buff

![image](https://github.com/user-attachments/assets/9c87aea6-9cac-4d05-a92b-6a75b26f7285)

</details>


## TL;DR

**As the sources and value of Damage % increase, SAs impact falls off, as it is seemingly additive, versus IR, who seems to be multiplicative to an extent, with damage %**

