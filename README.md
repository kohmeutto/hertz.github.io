## (b) CEM - Homogenous

### 1. Homogenous, 코시-오일러 제차미분방정식

아래와 같은 **코시-오일러 미분방정식**의 해를 구한다고 할 때,

1) 형태1

$$x^2y''+axy'+by=0$$

$$D^2+\left(a-1\right)D+b=0$$

2) 형태2

$$xy^{\prime}+ay=0$$

$$D+a=0$$

---

### 2. 서로 다른, 실수 해

\begin{align}
    D=\alpha,\beta$$
    y=c_1x^{\alpha}+c_2x^{\beta}
\end{align}

---

**example1)**

$$x^2y''-4xy'+6y=0$$

<details>
  <summary>sol</summary>

    $ \left(D-3\right)\left(D-2\right)=0\rightarrow D=3,2 $
    
    $ y=c_1x^3+c_2x^2 $

</details>


- sol
    
    $$
    \left(D-3\right)\left(D-2\right)=0\rightarrow D=3,2
    $$
    
    $$
    y=c_1x^3+c_2x^2
    $$
    

**example2)** @Seungmin Son 

$$
x^2y''-xy'-y=0
$$

- sol
    
    $$
    D^2-2D-1=0\rightarrow D=1\pm\sqrt{2}
    $$
    
    $$
    y=c_1x^{1+\sqrt{2}}+c_2x^{1-\sqrt{2}}
    $$
    

**example3)** @Seungmin Son 

$$
xy''-y'=0
$$

- sol
    
    $$
    D^{}\left(D-2\right)=0\rightarrow D=2,0
    $$
    
    $$
    y=c_1x^2+c_2
    $$
    

**example4)** 

$$
x^3y''+2x^2y'-6xy=0
$$

- sol
    
    $$
    \left(D+3\right)\left(D-2\right)=0\rightarrow D=-3,2
    $$
    
    $$
    y=c_1e^{-3x}+c_2e^{2x}
    $$
    

---

### 2. 중근

$$
D=\alpha
$$

$$
y=\left(c_1+c_2\ln x\right)x^{\alpha}
$$

---

**example1)**

$$
xy''+y'=0
$$

- sol
    
    $$
    D^2=0\rightarrow D=0
    $$
    
    $$
    y=c_1+c_2\ln x
    $$
    

**example2)**

$$
x^2y''-xy'+y=0
$$

- sol
    
    $$
    \left(D-1\right)^2=0
    $$
    
    $$
    y=\left(c_1+c_2\ln x\right)x
    $$
    

---

### 3. 서로 다른, 복소수 해

$$
D=\alpha\pm i\beta
$$

$$
y=x^{\alpha}\left(c_1\cos\left(\beta\ln x\right)+c_2\sin\left(\beta\ln x\right)\right)
$$

$$
y=c_1x^{\alpha+i\beta}+c_2x^{\alpha-i\beta}
$$

---

**example1)**

$$
x^2y''+xy'+y=0
$$

- sol
    
    $$
    D^2+1=0\rightarrow D=\pm i
    $$
    
    $$
    y=c_1\cos\left(\ln x\right)+c_2\sin\left(\ln x\right)
    $$
    

**example2)** @Seungmin Son 

$$
x^2y''+3xy'+3y=0
$$

- sol
    
    $$
    D^2+2D+3=0\rightarrow D=-1\pm i\sqrt{2}
    $$
    
    $$
    y=x^{-1}\left(c_1\cos\left(\sqrt{2}\ln x\right)+c_2\sin\left(\sqrt{2}\ln x\right)\right)
    $$
