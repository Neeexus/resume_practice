
---
# 기본 이력사항

<img src = gym.png height = 350 wight = 350>

# 이름 : 구영모
## 생년월일 : 1997.04.18
## 영문 성명 : Koo young mo
### 직업 : 대학생
### 병역 : 육군
## 좌우명 : **매일아침 삶의 목표를 생각하며 일어나라**

---
# 학력
<img src = school.JPG height = 150 wight = 150>

|재학기간|학력사항|전공|
|---|---|---|
|2003~2009|소양초등학교|-|
|2010~2012|소양중학교|-|
|2013~2015|봉의고등학교|이과|
|2016~2019|한림대학교|융합소프트웨어 학과|
|2019~현재|한림대학교|빅데이터 전공|

---
 # 자격증

|자격증|취득일자|
|---|---|
|ITQ정보기술자격|2014.10|
|운전면허 1종보통|2016.02|
|MOS 파워포인트|2016.07|
|MOS 엑세스|2016.07|
|컴퓨터활용능력1급 필기|2019.07|

---

# 관심 분야
* 데이터 사이언스
* 사물 인터넷
* 인공지능
* 게임 제작

---

# 프로그래밍 언어 스킬
1. C  
2. C++  
3. C# 
4. Java  
5. Python  
6. SQL
7. R

---
# Call
* Email : dudah0776@gmail.com
* github : [https://github.com/dudah0776](https://github.com/dudah0776)
---

# 보유 기술 및 사용도구
<img src = language.JPG height = 80 wight = 100>

* 주로 사용하는 언어는 Java, python 입니다.
* python, R 언어를 사용하여 데이터 전처리 및 시각화를 할 수 있습니다.
* python, R 언어를 사용하여 데이터 분석 및 머신러닝을 할 수 있습니다.
* 유니티의 사용법에 대해 알고 있습니다.
* 리눅스를 통하여 시스템에 관한 간단한 프로그래밍을 할 수 있습니다.
---

# 대학성적 요약
<img src = grade.JPG height = 150 wight = 100>

총 취득학점 : 87 평점평균 : 3.99

---

# 대학 생활 참여 프로젝트들
## 자바를 사용한 해시테이블 구현
```java
public class LinearProbing<K,V> {
	private int M = 13;
	private K[] a = (K[]) new Object[M];
	private V[] d = (V[]) new Object[M];
	private int hash(K key) {
		return (key.hashCode() & 0x7fffffff) % M; 
	}
	public void put(K key, V data) {
		int initialpos = hash(key);
		int i = initialpos, j = 1;
		do {
			if(a[i]==null) {
				a[i]=key;
				d[i]=data;
				return;
			}
			if(a[i].equals(key)) {
				d[i] = data;
				return;
			}
			i=(initialpos + j++)%M;
		}while(i!=initialpos);
	}
	public V get(K key) {
		int initialpos = hash(key);
		int i = initialpos, j = 1;
		do {
			if(a[i].equals(key)) return d[i];
			i = (initialpos+j++)%M;
		}while(a[i] != null && i!=initialpos);
		return null;
	}
	public V delete(K key) {
		int initialpos = hash(key);
		int i = initialpos, j = 1;
		do {
			if(a[i].equals(key)) a[i]=null; d[i]=null;
			i = (initialpos+j++)%M;
		}while(a[i] != null && i!=initialpos);
		return null;
	}
	public void print() {
		for(int i = 0 ; i<M ; i++) {
			System.out.print(i+"\t");
		}
		System.out.println();
		for(int j = 0 ; j<M ; j++) {
			System.out.print(a[j]+"\t");
		}				
	}
}
```
* 자바언어를 사용하여 해시테이블 구조에 대해 이해하고 해시테이블을 직접 구현하였다.

## 파이썬을 사용한 레드와인 품질 예측 및 분류

<img src = data.JPG height = 360 wight = 100>

* [kaggle](https://www.kaggle.com) 에서 수집한 레드 와인 데이터로 와인의 품질을 예측
* scikit-learn을 사용하여 최상의 데이터 예측 도구를 찾음
* 분류한 예측 도구를 가지고 세부 튜닝을 하여 와인의 품질예측의 질을 더욱 높임

## 유니티를 사용한 VR게임 개발

<img src = unity.JPG height = 320 wight = 100>

* 플레이어가 방안의 불을 끄고 다시 키면 방안의 바뀐 물체를 찾는 VR기반 게임
* C# 언어를 사용 하여 구현
* 유니티 엔진을 사용한 게임개발

---
# 앞으로의 포부 및 각오

## 남은 대학 생활을 뛰어난 소프트웨어 엔지니어가 되기 위해 누구보다 노력하고 열심히 하는  사람이 될 것 입니다.