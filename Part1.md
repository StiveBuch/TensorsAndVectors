Группа вращений и её алгебра Ли: Следуя стандартной нотации, обозначим через $SO(3)$ группу ортогональных преобразований, то есть $SO(3) := \{A: \mathbb{R}^3 \rightarrow \mathbb{R}^3 \, | \, A'A = AA' = I \text{ и } \det(A) = 1\}$. (1)

Для любого $A \in SO(3)$ существует собственный вектор $\omega \in \mathbb{R}^3$ такой, что $A\omega = \omega$. Геометрически, $A$ представляет собой вращение вокруг вектора $\omega$.

Касательное пространство к $SO(3)$ в единичной точке, обозначаемое $T_{SO(3)}$, является самой группой $SO(3)$. Множество антисимметричных тензоров, определенное как $\mathfrak{so}(3) := \{\xi \in \mathbb{R}^{3 \times 3} \, | \, \xi' = -\xi\}$, выступает в роли алгебры Ли для $SO(3)$. (2)

Для любого $\xi \in \mathfrak{so}(3)$ существует собственный вектор $v \in \mathbb{R}^3$ такой, что $\xi v = 0$. Это определяет изоморфизм $\Omega: \mathfrak{so}(3) \rightarrow \mathbb{R}^3$, заданный соотношением $\xi \mapsto \omega \times v$, где $\times$ обозначает векторное произведение в $\mathbb{R}^3$, а $v$ может быть любым ненулевым вектором в $\mathbb{R}^3$.

В дальнейшем мы обозначаем инерциальную (фиксированную) систему координат {E,} = {E1, E2, E3}, выбранную в качестве стандартной базы, где E1 = [1, 0, 0], E2 = [0, 1, 0], E3 = [0, 0, 1]. (2.4) Таким образом, E, = E'. Для любого элемента ξ из алгебры so(3) у нас есть матричное представление (относительно базы {E,}) вида ξ̂ = [0 -ξ₃ ξ₂; ξ₃ 0 -ξ₁; -ξ₂ ξ₁ 0]. (2.5) Любой элемент ξ из алгебры so(3) соответствует матрице A из группы SO(3) с помощью отображения exp(ξ̂) = A, где exp обозначает экспоненту матрицы.

Таким образом, E, = E'. Для любого ξ ∈ SO(3) у нас есть матричное представление (относительно {E,}):


$$
\[ ξ = \begin{bmatrix} 0 & -ξ_3 & ξ_2 \\ ξ_3 & 0 & -ξ_1 \\ -ξ_2 & ξ_1 & 0 \end{bmatrix} \quad (ξ ∈ so(3)) \] (2.5)
$$


Любое A ∈ SO(3) представляет собой бесконечно малое вращение вокруг вектора ω ∈ R³. Касательное пространство в точке A ∈ SO(3) определяется (с помощью левых или правых сдвигов SO(3)) следующим образом:

\[ T_{SO(3)} := \{ Aξ = AξA' \mid ξ ∈ SO(3) \text{ или } ξ = AξA' ∈ SO(3) \} \] (2.6)

Обратите внимание, что Aξ ∈ T_{SO(3)} может быть рассмотрено как конечное вращение, совмещенное с бесконечно малым вращением.

См. Рис. 4 для геометрической иллюстрации экспоненциального отображения. Замечательно, что для экспоненциального отображения существует следующее явное аналитическое представление:
\[ \exp(\Omega) = I + \sin(\|\Omega\|) \Omega/\|\Omega\| + (1 - \cos(\|\Omega\|))(\Omega/\|\Omega\|)^2 \quad (2.8a) \]
Альтернативно, используя формулы половинного угла, можно записать эквивалентное выражение для экспоненциального отображения в SO(3):
\[ \exp(\Omega) = I + \frac{\sin(\|\Omega\|)}{\|\Omega\|} \Omega + \frac{1 - \cos(\|\Omega\|)}{\|\Omega\|^2} \Omega^2 \]

