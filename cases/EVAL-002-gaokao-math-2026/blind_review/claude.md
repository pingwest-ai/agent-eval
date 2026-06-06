(n-k+1,k). Standard bijection (b_i=a_i-(i-1)). ✓ Correct proof. (III) Total sparse subsets (with |A|≥2) = F_{n+2}-n-1. The total number of subsets with no two consecutive (including empty and singletons) is F_{n+2}. Subtract empty (1) and singletons (n): F_{n+2}-1-n. ✓ Correct.

So Paper 7 Q21 is correct and elegant.

Summary Paper 7: Real errors in Q17(II) (sign) and Q20(III) (wrong range). Q16(II)② inconsistency (likely OCR or error). Q8 contextualization issue. Q19(II) under-justified. So命题质量 has notable problems. But the problem designs themselves (Q21 Fibonacci, Q19 pole-polar, Q15 Collatz) are interesting/innovative. Heavy OCR garbling limits full assessment.

Hmm, Paper 7 is interesting in design but has answer errors.

═══════════════════════ 试卷八 (Paper 8) ═══════════════════════

Selection answers (page 76): A A B B C C A A C B

Q1: M={x|-2<x≤3}, N={x|x²-2x-3≤0}={x|-1≤x≤3}. M∩N={x|-1≤x≤3}. Answer A. ✓ Q2: (1+i)z=2-i. z=(2-i)/(1+i)=(2-i)(1-i)/2=(2-2i-i+i²)/2=(2-3i-1)/2=(1-3i)/2=1/2-3/2 i. Conjugate z̄=1/2+3/2 i. Answer A. ✓ Q3: y²=4x, focus F(1,0). P(x0,2) on parabola: 4=4x0 → x0=1. |PF|=x0+1=2. Answer B=2. ✓ Q4: (2x-1/x)^5, coeff of x. T_{k+1}=C(5,k)(2x)^{5-k}(-1/x)^k=C(5,k)2^{5-k}(-1)^k x^{5-k-k}=C(5,k)2^{5-k}(-1)^k x^{5-2k}. 5-2k=1 → k=2. C(5,2)2³(-1)²=10·8=80. Answer B=80. ✓ Q5: a=(1,2), b=(m,1), a⊥(a-b). a-b=(1-m,1). a·(a-b)=(1)(1-m)+(2)(1)=1-m+2=3-m=0 → m=3. Answer C=3. ✓ Q6: arithmetic a2=3, a5=9. d=(9-3)/3=2, a1=a2-d=1. a10=a1+9d=1+18=19. Answer C=19. ✓ Q7: "a>b>0" vs "1/a<1/b". a>b>0 → 1/a<1/b (true, sufficient). Converse: 1/a<1/b doesn't imply a>b>0 (e.g., a=-1,b=-2: 1/a=-1, 1/b=-0.5, -1<-0.5 ✓ but a>b>0 false; actually a=-1>b=-2 but not >0). So sufficient not necessary. Answer A. ✓ Q8: f(x)=sin(2x+π/3) shifted left by φ, result symmetric about y-axis (even). g(x)=sin(2(x+φ)+π/3)=sin(2x+2φ+π/3). Even → 2φ+π/3=π/2+kπ → 2φ=π/6+kπ → φ=π/12+kπ/2. Min positive φ=π/12. Answer A. ✓ Q9: battery C(t)=C0 e^{-kt}. After 2 years, 90%: e^{-2k}=0.9 → -2k=ln0.9 → k=-ln0.9/2≈0.105/2≈0.0525. Replace when <70%: e^{-kt}=0.7 → t=-ln0.7/k≈0.357/0.0525≈6.8. Answer C=7年. ✓ Q10: |a|=|b|=2, a·b=2. c=xa+yb, |c|=2. |c|²=x²|a|²+y²|b|²+2xy(a·b)=4x²+4y²+4xy=4. So x²+y²+xy=1. Let s=x+y. x²+y²+xy=(x+y)²-xy=s²-xy=1 → xy=s²-1. x,y real roots of t²-st+(s²-1)=0, discriminant s²-4(s²-1)≥0 → -3s²+4≥0 → s²≤4/3 → s≤2/√3=2√3/3. Max x+y=2√3/3. Answer B. ✓

Fill-in (page 76): Q11: (1+2x)^6, x² coeff=C(6,2)2²=15·4=60. ✓ Q12: hyperbola x²/4-y²/5=1, focus to asymptote distance. a²=4,b²=5,c²=9,c=3. Asymptote: y=±(√5/2)x → √5 x∓2y=0. Distance from focus (3,0): |√5·3|/√(5+4)=3√5/3=√5. ✓ (Distance from focus to asymptote = b always; b=√5. ✓) Q13: sinα+cosα=√2. √2 sin(α+π/4)=√2 → sin(α+π/4)=1 → α+π/4=π/2 → α=π/4. ✓ Q14: composite solid, cube edge 2 + square pyramid (base = cube top, height √3). V=cube+pyramid=8+(1/3)(4)(√3)=8+4√3/3. ✓ Surface area: cube has 6 faces but top is covered by pyramid base. So 5 cube faces (bottom + 4 sides)=5·4=20. Plus pyramid 4 triangular faces. Pyramid: base edge 2, height √3. Slant height (apothem of triangular face)=√(height²+(base/2)²)=√(3+1)=2. Each triangular face area=(1/2)(2)(2)=2. 4 faces=8. Total surface=20+8=28. ✓ The answer (page 76): "V=8+4√3/3, S=28. ...组合体表面积=4(下底)+16(侧面)+8(棱锥侧)=28." Wait, 4(bottom)+16(sides of cube: 4 faces × 4=16)+8(pyramid)=28. ✓ Correct. Q15: f(x)=x²-2x (x≤1), ln x (x>1). Statements ①②③④, answer ②. ① continuous at x=1: left limit f(1⁻)=1-2=-1, right limit f(1⁺)=ln1=0. -1≠0, discontinuous. ① false. ② min on R: for x≤1, x²-2x has min at x=1 (vertex at x=1), f(1)=-1. Actually x²-2x on (-∞,1], vertex at x=1, value -1, and it's the min (parabola opening up, vertex at x=1 which is the right endpoint of domain). For x≤1, x²-2x is decreasing (since vertex at x=1, left of vertex decreasing)... wait vertex at x=1, for x<1 the function is decreasing toward the vertex. So min on (-∞,1] is at x=1: f(1)=-1. For x>1, lnx>0. So overall min=-1 at x=1. ② "f has min on R" — true, min is -1. ✓ (Answer includes ②.) ③ a∈(-1,0), f(x)=a has exactly 3 solutions. For x≤1: x²-2x=a. x²-2x-a=0, x=1±√(1+a). For a∈(-1,0), 1+a∈(0,1), √(1+a)∈(0,1). x=1+√(1+a)∈(1,2) — but this needs x≤1, so x=1+√(1+a)>1 rejected. x=1-√(1+a)∈(0,1)⊂(-∞,1] ✓ (one solution). For x>1: lnx=a<0, but lnx>0 for x>1, no solution. So only 1 solution. ③ "exactly 3 solutions" — false. ✓ (excluded) ④ for all x1≠x2, [f(x1)-f(x2)]/(x1-x2)≠0 (i.e., f injective / strictly monotonic, no two points with same value). Counterexample: f on (-∞,1] takes value... f(x)=x²-2x, and for x>1, f=lnx. Is there x1≤1 and x2>1 with f(x1)=f(x2)? f on (-∞,1]: range. At x=1, f=-1; as x→-∞, f→+∞. So on (-∞,1], f decreasing from +∞ to -1, range [-1,∞). For x>1, lnx∈(0,∞). So values in (0,∞) are achieved both on (-∞,1] (some x≤1 with x²-2x=v>0, i.e., x=1-√(1+v)<1... for v>0, 1+v>1, √(1+v)>1, x=1-√(1+v)<0) and on (1,∞). So e.g., f=1: x²-2x=1 → x=1±√2, x=1-√2≈-0.41≤1 ✓, f(1-√2)=1. And lnx=1 → x=e>1, f(e)=1. So f(1-√2)=f(e)=1, with 1-√2≠e. So [f(x1)-f(x2)]/(x1-x2)=0. ④ "for all x1≠x2, ≠0" is false (we found a pair with equal values). ✓ (excluded) So answer ② only. ✓ Correct. (The answer's reasoning matches: "①不连续. ②f最小值-1. ③1解. ④取x1=1-√2,x2=e, f(x1)=f(x2)=1,差商为0. 故只有②正确.") ✓

Solving (pages 77-78): Q16: b cosC+c cosB=2a cosA. (I) Projection formula: b cosC+c cosB=a. So a=2a cosA → cosA=1/2 → A=π/3. ✓ (II) Conditions. ③ a=1,b=2: 1=4+c²-2·2·c·(1/2)=4+c²-2c → c²-2c+3=0, Δ=4-12<0, no solution. Triangle doesn't exist. ✓ (correctly excluded) ① a=2√3, b=2: 12=4+c²-2·2·c·(1/2)=4+c²-2c → c²-2c-8=0 → (c-4)(c+2)=0 → c=4. S=(1/2)(2)(4)(√3/2)=2√3. ✓ ② a=7, b=5: 49=25+c²-2·5·c·(1/2)=25+c²-5c → c²-5c-24=0 → (c-8)(c+3)=0 → c=8. S=(1/2)(5)(8)(√3/2)=10√3. ✓ Correct.

Q17: P-ABCD, base rectangle AB=2, AD=1, PA⊥base, PA=2. E midpoint PC. Coords: A(0,0,0), B(2,0,0), D(0,1,0), C(2,1,0), P(0,0,2), E=midpoint PC=(1,1/2,1). (I) PA∥plane BDE. Take F=midpoint BD=(1,1/2,0). EF=E-F=(0,0,1)∥PA=(0,0,-2). EF⊂plane BDE, PA⊄, so PA∥plane BDE. ✓ (II) Dihedral P-BD-E cosine. Plane BDE normal n1=BD×BE. BD=D-B=(-2,1,0), BE=E-B=(-1,1/2,1). n1=BD×BE=|i j k;-2 1 0;-1 1/2 1|=i(1·1-0·1/2)-j((-2)·1-0·(-1))+k((-2)·1/2-1·(-1))=i(1)-j(-2)+k(-1+1)=(1,2,0). Plane PBD normal n2=BD×BP. BP=P-B=(-2,0,2). n2=BD×BP=|i j k;-2 1 0;-2 0 2|=i(1·2-0·0)-j((-2)·2-0·(-2))+k((-2)·0-1·(-2))=i(2)-j(-4)+k(2)=(2,4,2)→(1,2,1). cos<n1,n2>=(1·1+2·2+0·1)/(√5·√6)=(1+4+0)/(√30)=5/√30=5√30/30=√30/6. The answer (page 77): "n1=(1,2,0), n2=(1,2,1), cos=5/(√5·√6)=√30/6." ✓ But is the dihedral P-BD-E acute or obtuse? cos=√30/6≈0.913 (positive). The answer gives √30/6. Let me verify the sign is right. Actually, let me compute the actual dihedral with perpendicular vectors. Edge BD, midpoint... let me use point on BD. O=midpoint BD=(1,1/2,0). Face PBD, point P: OP=P-O=(-1,-1/2,2). Perp to BD: BD=(-2,1,0). OP·BD=2-1/2+0=3/2. |BD|²=5. OP_perp=OP-(3/2/5)BD=(-1,-1/2,2)-(3/10)(-2,1,0)=(-1+6/10,-1/2-3/10,2)=(-0.4,-0.8,2)=(-2/5,-4/5,2). Face BDE, point E: OE=E-O=(0,0,1). OE·BD=0. So OE_perp=OE=(0,0,1). cos(dihedral)=OP_perp·OE_perp/(|OP_perp||OE_perp|)=((-2/5)(0)+(-4/5)(0)+(2)(1))/(|(-2/5,-4/5,2)|·1)=2/√(4/25+16/25+4)=2/√(20/25+4)=2/√(0.8+4)=2/√4.8=2/2.19=0.913=√30/6? √30/6≈5.477/6≈0.913. ✓ And positive, so acute. cos=√30/6. ✓ Correct! Good. (III) Line BE with plane PBD, sin. BE=(-1,1/2,1), |BE|=√(1+1/4+1)=√(9/4)=3/2. n2(PBD)=(1,2,1). sinθ=|BE·n2|/(|BE||n2|)=|-1+1+1|/((3/2)√6)=|1|/((3/2)√6)=1/((3/2)√6)=2/(3√6)=2√6/18=√6/9. ✓ Correct.

Q18: autonomous driving algorithms A, B. Table: 雨天 200 (A:180, B:150), 晴天 500 (A:480, B:470), 雪天 300 (A:270, B:240). (I) pA=(180+480+270)/1000=930/1000=0.93. ✓ (II) From 雨天 200, pick 1 scene. X=A success (0/1), Y=B success. P(X=1)=180/200=0.9, P(Y=1)=150/200=0.75. X,Y independent. Z=X+Y. P(Z=0)=0.1·0.25=0.025. P(Z=1)=0.1·0.75+0.9·0.25=0.075+0.225=0.3. P(Z=2)=0.9·0.75=0.675. E(Z)=0+0.3+2·0.675=0.3+1.35=1.65. ✓ (Also E(X)+E(Y)=0.9+0.75=1.65.) (III) pB=(150+470+240)/1000=860/1000=0.86. P(both fail)=（1-0.93)(1-0.86)=0.07·0.14=0.0098. P(at least one)=1-0.0098=0.9902. ✓ Correct.

Q19: ellipse x²/4+y²/3=1, A left vertex. (I) a=2, b²=3, c²=1, c=1. e=1/2. Right focus F(1,0). ✓ (II) P(1,0), line l slope k≠0 meets C at M,N. AM, AN slopes k1,k2. Prove k1k2 constant. A=(-2,0). Line y=k(x-1). Substitute 3x²+4y²=12: 3x²+4k²(x-1)²=12 → (3+4k²)x²-8k²x+4k²-12=0. x1+x2=8k²/(3+4k²), x1x2=(4k²-12)/(3+4k²). k1k2=[y1/(x1+2)][y2/(x2+2)]=y1y2/[(x1+2)(x2+2)]. y1y2=k²(x1-1)(x2-1)=k²[x1x2-(x1+x2)+1]=k²[(4k²-12)/(3+4k²)-8k²/(3+4k²)+1]=k²[(4k²-12-8k²+3+4k²)/(3+4k²)]=k²[(-9)/(3+4k²)]=-9k²/(3+4k²). (x1+2)(x2+2)=x1x2+2(x1+x2)+4=(4k²-12)/(3+4k²)+16k²/(3+4k²)+4=(4k²-12+16k²+12+16k²)/(3+4k²)=(36k²)/(3+4k²). k1k2=[-9k²/(3+4k²)]/[36k²/(3+4k²)]=-9k²/36k²=-1/4. ✓ Correct.

Q20: f(x)=ln(1+x)-ax. (I) a=1/2: f(x)=ln(1+x)-x/2, f(0)=0, f'(x)=1/(1+x)-1/2, f'(0)=1-1/2=1/2. Tangent y=x/2. ✓ (II) f decreasing on (0,∞), find a. f'(x)=1/(1+x)-a≤0 on (0,∞) → a≥1/(1+x) for all x>0. sup of 1/(1+x) on (0,∞) is 1 (as x→0+). So a≥1. a∈[1,∞). ✓ (III) a=1: prove for x>0, f(x)<-x²/2+x³/3, i.e., ln(1+x)-x<-x²/2+x³/3, i.e., ln(1+x)<x-x²/2+x³/3. Define g(x)=x-x²/2+x³/3-ln(1+x). g(0)=0. g'(x)=1-x+x²-1/(1+x)=[(1-x+x²)(1+x)-1]/(1+x). (1-x+x²)(1+x)=1+x-x-x²+x²+x³=1+x³. So g'(x)=[1+x³-1]/(1+x)=x³/(1+x). For x>0, g'>0, g increasing, g(x)>g(0)=0. So ln(1+x)<x-x²/2+x³/3. ✓ Correct.

Q21: M={1,...,8}, f(S)=sum of elements. (I) f(S)=10, count subsets. The answer lists: 2-element {2,8},{3,7},{4,6} (3); 3-element {1,2,7},{1,3,6},{1,4,5},{2,3,5} (4); 4-element {1,2,3,4} (1). Total 8. Let me verify exhaustively. Subsets of {1,...,8} summing to 10.

- 1 element: {10}? No, max is 8. None.
- 2 elements: {2,8},{3,7},{4,6}. Also {a,b} a+b=10, a<b, a,b∈1..8: (2,8),(3,7),(4,6). Not (5,5). So 3. ✓
- 3 elements: a+b+c=10, distinct, 1..8. {1,2,7},{1,3,6},{1,4,5},{2,3,5}. Let me find all. Smallest element 1: 1+b+c=10, b+c=9, b<c, b,c∈2..8: (2,7),(3,6),(4,5). So {1,2,7},{1,3,6},{1,4,5}. Smallest 2: 2+b+c=10, b+c=8, b<c, b,c∈3..8: (3,5). {2,3,5}. (Not (4,4).) Smallest 3: 3+b+c=10, b+c=7, b<c, b,c∈4..8: none (4+5=9>7? wait 4+3 no, b≥4, min b+c=4+5=9>7). None. So 3-element: 4. ✓
- 4 elements: a+b+c+d=10, distinct min sum 1+2+3+4=10. So {1,2,3,4}. Only one. ✓
- 5+ elements: min sum 1+2+3+4+5=15>10. None. Total: 3+4+1=8. ✓ Correct. (II) |S|=5, prove two different subsets with equal f. S has 2^5=32 subsets. f values range 0 to f(S). Max f(S) for |S|=5 is 4+5+6+7+8=30. So f∈{0,...,30}? Actually f of subsets of S ranges 0 to f(S)≤30. Number of possible values ≤31. 32 subsets, ≤31 values, pigeonhole → two subsets same f. ✓ Correct. (III) T family of distinct subsets with distinct f values, max n. f(S)∈{0,1,...,36} (since 1+2+...+8=36). 37 possible values. So n≤37. Construction: for each k∈{0,...,36}, some subset sums to k (since {1,...,8} can represent all 0..36 — actually can it? 1,2,4,8 can make 0..15, but we have all of 1..8. Can we make every integer 0..36? With subset sums of {1,2,3,4,5,6,7,8}. The subset sums of {1,...,8} cover 0 to 36 contiguously? Yes — with 1 and 2 you can adjust by 1, and the set is "complete" (each element ≤ 1+sum of smaller). 1≤1, 2≤1+1=2, 3≤1+2+1... actually the condition for subset sums to be contiguous 0..total is that when sorted, each a_{i+1}≤1+sum(a_1..a_i). 1: ok. 2≤1+1=2 ok. 3≤1+1+2=4 ok. 4≤1+1+2+3=7 ok. etc. So yes, all 0..36 achievable. So 37 subsets with distinct sums 0..36. n=37. ✓ Correct.

Paper 8: I found NO errors. All selection, fill-in, and solving questions are correct and well-reasoned. Clean paper. Coverage comprehensive. Has nice contextualized problems (battery decay Q9, drones Q14, autonomous driving Q18). Good difficulty progression. The Q21 (subset sums) is a solid combinatorics capstone, though perhaps slightly less novel than some others.

So Paper 8 is error-free and well-constructed, with good contextualization. Strong.

═══════════════════════ NOW LET ME SYNTHESIZE ═══════════════════════

Error summary:

- Paper 1: No errors found. Minor: Q16 conditions 1&2 both lead to same triangle (redundancy, not error). Strong, clean, good difficulty and innovative capstone (m-完备列).
- Paper 2: Heavily OCR-garbled problem statements; couldn't fully verify. Answer key appears internally consistent. Independent-set/Fibonacci capstone is good. Verification limited.
- Paper 3 ("Mavis"): TWO clear errors — Q9 (e^x-x-a=0 exactly one root: answer B=[1,∞) wrong, correct a=1, no valid option) and Q15 (statement ② "max=1" wrongly marked correct; f unbounded above; answer should be ①③④ not ①②③④). Minor: Q7 open/closed interval ambiguity; Q17 cross-product sign typo (answer still correct); Q21(3) necessity hand-wavy.
- Paper 4: One clear error — Q18 distribution table doesn't sum to 1 (P(X=1)=7/72 and P(X=2)=19/72 wrong; should be 1/24 and 11/72; total comes to 7/6≠1). Heavy OCR garbling otherwise; other verifiable parts correct.
- Paper 5: One error — Q17 condition① dihedral E-BF-C: answer √2/2 wrong (treats plane BFC as base when F is off-base); correct |cos|=1/2 (actual -1/2). Condition② correct. Otherwise strong, elegant problems (GF(2) cyclic capstone, extremum-shift).
- Paper 6: No errors found. Clean, comprehensive, but conventional/routine problem types (lower innovation). Footer "AI生成".
- Paper 7: TWO+ errors — Q17(II) dihedral P-BD-C: answer √3/3 wrong sign (dihedral obtuse, correct -√3/3); Q20(III): answer (0,1] wrong (fabricated a>0; correct (-∞,1]). Plus Q16② a²=2 vs a=2 inconsistency, Q8 contextualization mismatch, Q19(II) under-justified (relies on pole-polar, syllabus-edge). Heavy OCR garbling. Interesting designs though.
- Paper 8: No errors found. Clean, comprehensive, good contextualization (battery, drones, autonomous driving). Solid. Slightly conventional capstone.

So the cleanest, error-free papers: 1, 6, 8 (and possibly 2 but unverifiable). Papers with errors: 3 (2 errors), 4 (1 error), 5 (1 error), 7 (2+ errors).

For scoring, I need to weigh:

- 试卷结构 (structure)
- 考点覆盖 (coverage)
- 难度梯度 (difficulty gradient)
- 命题质量 (quality — errors hurt this most)
- 创新与趋势 (innovation/trends — contextualization, novel problems)

Let me think about the Beijing Gaokao context. The standard Beijing structure: 10 选择 (5×... wait). Actually Beijing 卷: 选择题10题×4分=40, 填空5题×5分=25, 解答6题×85分... let me recall. Beijing math: 选择10×4=40, 填空5×5=25, 解答6题 (13+14+13/14+15+15+...) totaling 85. Total 150. All papers follow this. Good structural conformity across the board.

Beijing characteristics:

- Q15 (last fill-in) is often a multi-statement 真假判断 — papers 2,3,4,5,6(?),7,8 have this. Paper 1 has a different Q15 (ln x=ax roots). Actually Beijing's 填空压轴 (Q15) is classically the "判断正确结论序号" multi-statement. Papers 2,3,4,5,7,8 have it; Paper 1 and 6 don't (Paper 6 Q15 is "write a function", Paper 1 Q15 is parameter range). So Papers 2,3,4,5,7,8 better match Beijing's Q15 style.
- Beijing 解答题 structure: 三角 (16), 立体几何 (17), 概率统计 (18), 解析几何 (19), 导数 (20), 新定义/创新 (21). All papers follow this 16-21 pattern closely. Excellent conformity.
- Beijing's Q21 is famously a 新定义 (new-definition) problem requiring abstraction. All papers have this:
  - P1: m-完备列 (binary representation) ✓ excellent fit
  - P2: independent sets / Fibonacci ✓
  - P3: Rp数列 (novel sequence) ✓ but harder/messier
  - P4: 好排列 (permutations, |diff|≤2) ✓
  - P5: 可约零序列 (GF(2) linear algebra) ✓ excellent, but GF(2)/linear algebra framing is arguably beyond typical gaokao tools (though solvable elementarily)
  - P6: subset sums f(S) ✓ but more standard
  - P7: 疏离子集 (Fibonacci) ✓ similar to P2
  - P8: subset sums f(S) ✓ (very similar to P6)
- Beijing's 选择/填空 increasingly include 情境化 (contextualized) problems. The contextualized problems:
  - P1: Q9 growth model N(t) (logistic) ✓
  - P2: Q7 ML training error ✓
  - P3: none obvious in selection (more traditional)
  - P4: Q9 battery energy density ✓
  - P5: Q7 compute cost C(x)=kx log2 x ✓, Q9 rainwater collector ✓
  - P6: Q7 pyramid (not contextualized really)... actually P6 has fewer contextualized. Q's are classic.
  - P7: Q8 charging station coverage (muddled)
  - P8: Q9 battery decay ✓, Q14 drone ✓, Q18 autonomous driving ✓ (most contextualized!)

So for 创新与趋势: P8 has the most contextualized problems (battery, drone, autonomous driving), P5 has good ones (compute cost, GF(2) capstone), P1 has logistic growth + elegant capstone. P3, P6 are more traditional/routine.

Now, the AI-relevance: many papers embed AI/tech themes (P1 "增长模型"/三个模型 probability, P2 ML training error + "甲乙丙模型", P4, P5 robot testing + compute cost, P7 charging stations, P8 autonomous driving). Interesting since these are AI-generated papers — they inject AI/tech contexts. Heck (tech journalist) would find this notable. I can mention it.

Let me also reconsider difficulty gradient. Beijing's difficulty: selection/fill mostly easy-medium with Q10/Q15 harder; solving 16-19 medium, 20-21 hard. All papers roughly follow.

Let me think about which is best (Top 1):

- Paper 1: Error-free, excellent structural fit, strong capstone (m-完备列 is very Beijing-flavored — it's almost identical in spirit to real Beijing 新定义 problems), good coverage, decent contextualization (logistic growth, probability with "models"). Clean. This is a top contender.
- Paper 8: Error-free, excellent contextualization (most "情境化" — drone, battery, autonomous driving fits the 趋势 best), good structure, solid capstone. Also top contender. The Q15 multi-statement is well-constructed.
- Paper 5: Strong, elegant problems, but has one dihedral error (Q17①). The GF(2) capstone is brilliant but maybe slightly beyond-syllabus framing.
- Paper 6: Error-free but conventional/routine, lower innovation. Solid but unexciting.

Between Paper 1 and Paper 8 for Top 1. Both error-free.

- Paper 1's capstone (m-完备列, binary) is more aligned with classic Beijing 新定义 elegance and has clean (I)(II)(III) progression. Its contextualization is moderate.
- Paper 8 has the best 情境化/趋势 alignment (drone/battery/autonomous driving), error-free, but its capstone (subset sums) is solid-but-standard, and very similar to Paper 6's.

Hmm. I think Paper 1 edges it for overall命题质量 + capstone quality + cleanliness, but Paper 8 wins on 创新与趋势 (contextualization). Let me think about which to crown.

Actually, given the evaluation emphasizes "情境化、减少机械计算、增加思维含量" as the trend, Paper 8's heavy contextualization is a plus. But Paper 1's capstone is more intellectually substantial and Beijing-authentic. Both are error-free which is the most important thing.

Let me reconsider Paper 5 more — it's arguably the most intellectually impressive (the GF(2) capstone is genuinely elegant, the extremum-shift problem in Q20 is sophisticated, the cumulative-scoring probability is well-designed). But the Q17① error costs it. If I weight命题质量 heavily, the error drops it below the error-free papers. But its other dimensions are very high.

I think for Top 1, I'll go with Paper 1 — it's error-free, has the strongest combination of structural authenticity, a genuinely Beijing-flavored elegant capstone, comprehensive coverage, reasonable contextualization, and clean execution throughout. Paper 8 is a very close second (best contextualization, also error-free). I'll explain both and pick Paper 1, noting Paper 8 is nearly tied (could mention if someone prioritizes 情境化, Paper 8 might be preferred).

Actually, let me reconsider once more. Let me re-examine Paper 1 for true Beijing-fit and quality. Paper 1:

- Structure: 10+5+6, 40+25+85. ✓ Standard.
- Q15: ln x=ax range (not the multi-statement). This is slightly less "Beijing Q15 style" (Beijing Q15 is usually multi-statement 判断). Minor.
- Q16: triangle with 条件选择 (choose condition) — very Beijing. ✓
- Q18: probability with 甲乙丙模型, distribution+expectation+decision. Good, contextualized (AI models). ✓
- Q20: ln(1+x)-ax, monotonicity + inequality proof. Classic Beijing 导数. ✓ Clean.
- Q21: m-完备列, binary representation. Excellent 新定义. ✓
- Contextualization: Q9 logistic growth, Q18 model accuracy. Moderate. All correct. Very solid.

Paper 8:

- Q15: multi-statement (more Beijing-authentic Q15). ✓
- Q16: 条件选择 with feasibility (③ rejected). Very Beijing. ✓
- Q9, Q14, Q18: heavy contextualization. ✓✓✓
- Q21: subset sums (good but standard). All correct.

Both excellent. I'll crown Paper 1 but acknowledge Paper 8 closely. Actually, you know what, let me reconsider — Paper 8's Q15 multi-statement and 条件选择 Q16 with infeasible option are MORE authentically Beijing than Paper 1's Q15 (parameter range) and Q16 (both conditions valid, redundant). And Paper 8's contextualization aligns better with the stated 趋势. And both are error-free.

Hmm, this is close. Let me weigh: 命题质量 — both error-free, but Paper 1's Q16 redundancy (both conditions → same triangle) is a tiny design flaw, while Paper 8's Q16 (one infeasible condition, two distinct valid) is better designed. Paper 8's Q15 is more authentic. Paper 8's contextualization is stronger. So actually Paper 8 might edge Paper 1.

But Paper 1's capstone (m-完备列) is more elegant/substantial than Paper 8's (subset sums + pigeonhole, which is more routine). The capstone matters a lot for a Beijing paper's 思维含量.

OK here's my call: I'll make this genuinely close and pick based on the totality. I think I'll give Paper 1 and Paper 8 the top two scores, very close. For Top 1, I'll go with Paper 8 for its superior 情境化/趋势 alignment and more authentic Beijing Q15/Q16 design, both error-free, while noting Paper 1 is essentially tied and has a more elegant capstone. Actually, no — let me reconsider whether the capstone quality should tip it to Paper 1.

Ugh, I'm going back and forth. Let me just make a decision and justify it clearly. Both are error-free and excellent. The differentiators:

- Paper 8 advantages: best contextualization (3 strong contextualized problems vs Paper 1's ~2 moderate), authentic Beijing Q15 multi-statement, well-designed Q16 (infeasible option teaches 存在性判断), strong full-coverage.
- Paper 1 advantages: more elegant/substantial capstone (binary representation, a classic beautiful problem), equally clean.

For a Beijing predicted paper where 趋势 (情境化, 思维含量) is emphasized, and given both are error-free, I think Paper 8 is the best all-around because it nails the contextualization trend hardest while remaining rigorous and error-free, with authentic Beijing item types. But Paper 1's capstone is superior.

Decision: I'll rank Paper 8 #1 and Paper 1 #2, but very close, and I'll be explicit that Paper 1's capstone is more elegant and it's essentially a tie at the top. Actually, let me reconsider the scores to make them reflect this.

Hmm, actually, let me reconsider giving Paper 1 the edge. The thing is, the capstone (Q21 新定义) is the signature of a Beijing paper and carries enormous weight in distinguishing quality. Paper 1's m-完备列 is a genuinely excellent, clean, well-scaffolded 新定义 problem that mirrors real Beijing problems beautifully. Paper 8's subset-sum capstone is fine but more pedestrian (pigeonhole + greedy construction are standard). On 命题质量 and 思维含量 of the capstone, Paper 1 > Paper 8. On 情境化, Paper 8 > Paper 1.

I'll call it for Paper 1 as Top 1 on the strength of its capstone + overall cleanliness + still-good contextualization, with Paper 8 a very close second (and explicitly note Paper 8 wins if you prioritize 情境化). This gives a defensible, nuanced answer. Actually, both defensible. Let me go with Paper 1 as #1 since the capstone elegance + zero errors + strong all-around is the safest "best predicted Beijing paper" call, and 新定义 quality is the crown jewel of Beijing math.

Wait, I realize I should double-check: does Paper 1 have a multi-statement Q15? No, it's a parameter-range problem. Real Beijing 2021-2025 Q15 (填空压轴):

- 2021: 真假判断 multi-statement? Actually Beijing's 填空 last one varies. Recent Beijing has 数学探究/多选式填空. Let me not overstate. Both styles appear. Paper 1's Q15 is fine.

OK let me also reconsider — for 最不推荐 (least recommended): Paper 7 has 2+ clear errors (Q17 sign, Q20 wrong range) plus contextualization muddle (Q8) and under-justified Q19. OR Paper 3 has 2 clear errors (Q9 — which is severe, no valid option exists — and Q15).

Paper 3's Q9 is particularly bad: the problem itself is broken (correct answer a=1 isn't among the options) AND the answer/explanation is internally contradictory (says "min≥0 ⟺ a≥1" which is mathematically backwards). That's a severe命题质量 failure — a broken problem with a self-contradictory solution. Plus Q15 wrong. So Paper 3 has a "fatal" problem (Q9 unsolvable as posed).

Paper 7 has 2 answer errors but the problems themselves are mostly well-posed (Q17 and Q20 are valid problems, just wrong answers in the key; Q8 is muddled).

Between Paper 3 and Paper 7 for 最不推荐: Paper 3's Q9 being a fundamentally broken problem (no correct option) is worse than wrong answer keys. A broken problem can't be used at all. So Paper 3 might be 最不推荐. But Paper 7 also has issues and heavy garbling.

Hmm, but Paper 3 otherwise has good structure and the rest is mostly fine. Paper 7 has more scattered issues. Let me think about total quality.

Actually, for 最不推荐, I think Paper 3 is the call because:

1. Q9 is a genuinely broken problem (correct answer not among options, self-contradictory solution) — this is the most serious type of defect.
2. Q15 has a wrong answer (② wrongly included).
3. Plus minor issues. A broken problem is disqualifying for a usable exam.

But wait — Paper 7 also has a wrong final answer in Q20(III) (which is a clean logical error, claiming a>0 that isn't given) and a sign error in Q17(II). And Q16② inconsistency. And Q8 muddle. That's arguably more total defects than Paper 3.

Let me count clear errors:

- Paper 3: Q9 (broken problem + wrong answer + contradictory solution) — counts as severe; Q15 (wrong answer). = 2 errors, 1 severe (broken).
- Paper 7: Q17(II) (sign error), Q20(III) (wrong range), Q16② (inconsistency, maybe OCR). = 2 clear errors + 1 ambiguous.

Both have 2 clear errors. Paper 3's Q9 is more severe (unsolvable). Paper 7's are wrong-answer-key (problems are solvable, just keyed wrong).

For "最不推荐," I'll go with Paper 3, primarily because Q9 is a fundamentally unsolvable/broken problem (no correct option), which is the worst kind of defect for an exam — a student would waste time and there's no right answer. Combined with the Q15 error, Paper 3 has the most damaging命题质量 issues. I'll note Paper 7 is also weak (close to 最不推荐).

Hmm, but actually, let me reconsider whether Paper 2 or 4 should be in contention. Paper 2 is unverifiable (OCR), so I can't fairly call it worst. Paper 4 has the Q18 distribution error (1 error). So Paper 4 has fewer errors than 3 or 7.

So 最不推荐 is between Paper 3 and Paper 7. I'll pick Paper 3 (broken Q9 + wrong Q15), with Paper 7 noted as comparably weak.

Now let me assign scores (1-10 per dimension). Let me be calibrated. The instruction says don't anchor/compress — evaluate each independently. But I'll keep relative ordering sensible.

Let me define rough rubric per dimension:

- 试卷结构: Does it match Beijing format (10选择×4, 5填空×5, 6解答=85; 16-21 sequence: 三角/立几/概率/解几/导数/新定义)? Almost all do well → 8-9 range. Deduct for missing 参考公式, weird numbering (but that's format, ignore). Actually structure is about 题型/分值/题量, which all papers nail. So most get 8-9.
- 考点覆盖: function/derivative, trig, sequence, solid geometry, analytic geometry, probability/stats, plus 复数/集合/向量/二项式/circle etc. Check breadth. Most cover well.
- 难度梯度: easy→hard progression, discrimination, capstone difficulty matching Beijing.
- 命题质量: rigor, correctness (errors hurt heavily), no 超纲/错题. THIS is where errors drop scores.
- 创新与趋势: 情境化, openness, novelty, 思维含量, reduced 套路.

Let me score each:

Paper 1:

- 试卷结构: 9 (textbook Beijing structure, clean)
- 考点覆盖: 9 (集合复数抛物线函数二项式三角向量立几logistic数列; fill: 定义域抛物线三角立几对数; solving covers all核心板块; comprehensive). Maybe missing 圆 (no circle problem) and 统计 (probability yes, but 统计描述 light). Still 8-9. I'll say 9.
- 难度梯度: 9 (smooth, Q10/Q15 appropriately hard, Q21 substantial)
- 命题质量: 9 (error-free; tiny Q16 redundancy). High.
- 创新与趋势: 8 (logistic growth, model-accuracy probability, elegant capstone; moderate contextualization, capstone is novel but classic-flavored). 8. Total: 44/50.

Paper 2:

- 试卷结构: 9 (proper Beijing structure, has 参考... actually standard)
- 考点覆盖: 8 (covers broadly per answer key — 集合复数双曲线函数三角二项式条件立几向量数列; fill: 抛物线三角等差数列etc; capstone independent sets). Comprehensive but unverifiable.
- 难度梯度: 8 (seems reasonable)
- 命题质量: 6 (can't verify due to garbling; answer key internally consistent where readable; the impossibility of full verification + the heavy garbling itself, even if extraction-caused, means I can't vouch; I'll give middle score with caveat). Actually since I can't find errors but also can't verify, I'll be moderate. The instruction says忽略格式 but garbling prevents content check. I'll give 6-7 reflecting uncertainty, not penalizing for unseen content but unable to award high命题质量 without verification. 6.5→ I'll say 7 but heavily caveated. Hmm. Let me give 7 and note the verification limitation prominently.

Hmm, actually scoring Paper 2 is tricky. Since I genuinely can't verify, I should be transparent rather than precise. Let me give it moderate scores across the board with a clear caveat that it's based on the legible answer key and structure only. I'll note its ranking is provisional.

- 创新与趋势: 8 (ML training error context Q7, model probability Q18, independent-set capstone — good) Let me set Paper 2: structure 9, coverage 8, gradient 8, quality 7(caveat), innovation 8. Total 40. (Provisional.)

Paper 3:

- 试卷结构: 9 (proper structure)
- 考点覆盖: 9 (集合复数圆二项式数列三角指数函数向量; fill抛物线三角二项式球面奇函数; solving三角/立几/概率/解几/导数/新定义 — comprehensive, includes 圆 which others lack)
- 难度梯度: 7 (reasonable, but Q9 broken disrupts; Rp数列 capstone is hard/messy)
- 命题质量: 4 (Q9 broken problem — no valid option + self-contradictory solution; Q15 wrong answer; minor Q7 ambiguity, Q21③ hand-wavy). Two errors, one severe/disqualifying. Low. 4.
- 创新与趋势: 7 (Rp数列 is novel; but selection problems more traditional; less contextualization than P5/P8) Total: 36/50.

Paper 4:

- 试卷结构: 9
- 考点覆盖: 8 (集合复数双曲线三角数列二项式条件函数; fill函数抛物线三角球体函数; solving立几/三角/概率/解几/导数/排列新定义 — good; missing 圆?; covers核心)
- 难度梯度: 8 (reasonable; permutation capstone good)
- 命题质量: 5 (Q18 distribution error — doesn't sum to 1, two wrong probabilities; heavy garbling limits further check; other verifiable parts correct). One clear error + verification limits. 5-6. I'll say 6 (one error, otherwise what's verifiable is sound, but garbling). Hmm, one clear computational error in a distribution table (sums to 7/6) is a real quality issue. 6.
- 创新与趋势: 8 (battery energy density Q9, robot/投篮 probability; permutation capstone with 容斥 is nice; decent contextualization) Total: 39/50.

Paper 5:

- 试卷结构: 9
- 考点覆盖: 9 (集合复数圆二项式三角数列函数向量; fill抛物线三角二项式圆柱球奇函数; solving三角/立几/概率/解几/导数/GF2新定义 — comprehensive, includes 圆)
- 难度梯度: 9 (excellent — Q10 vector dot product, Q15 multi-statement, Q20 extremum-shift, Q21 GF(2) — strong discrimination)
- 命题质量: 6 (Q17① dihedral error — wrong plane, √2/2 vs correct -1/2; otherwise rigorous and sophisticated). One error in an optional sub-part. The rest is very high quality. 6-7. The error is real but isolated; the overall rigor elsewhere is excellent. I'll say 7 (one isolated error in one of two optional conditions, otherwise top-tier rigor). Hmm, but it's a conceptual error (treating off-base plane as base), not a typo. Still, condition② is correct. I'll give 7.

Actually, let me reconsider. The error in Paper 5 Q17① is a genuine conceptual mistake (the solver assumed plane BFC = base when F is the midpoint of PC, which is off the base). That's not a typo, it's a real error that gives a wrong answer for that branch. But it's one branch of one sub-question. Comparing to Paper 4's Q18 (distribution doesn't sum to 1 — a more glaring/checkable error), Paper 5's is subtler. I'll give Paper 5命题质量 7 (one conceptual error in an optional branch, but exceptional rigor and sophistication elsewhere — the GF(2) capstone and extremum-shift are flawless and advanced).

- 创新与趋势: 9 (compute-cost context Q7, rainwater collector Q9, robot testing Q18 with optimization comparison, GF(2) capstone — highly innovative, strong 思维含量) Total: 9+9+9+7+9 = 43/50.

Paper 6:

- 试卷结构: 9 (proper, has 参考公式 explicitly — nice touch)
- 考点覆盖: 9 (集合复数函数三角向量数列立几概率抛物线指数; fill分段函数二项式向量双曲线偶函数; solving三角/数列/立几/概率/解几/导数 — comprehensive). Note: Paper 6's Q21 is 导数 (e^x-ax-1) not a 新定义! Wait. Let me check. Paper 6 solving: 16三角, 17数列, 18立几, 19概率(竞赛), 20解几(抛物线), 21导数(e^x-ax-1). So Paper 6 does NOT have a 新定义 capstone! Its Q21 is a standard 导数 problem. This is a STRUCTURAL deviation from Beijing — Beijing's Q21 is always a 新定义/创新 problem. Paper 6 replaced it with a routine 导数 inequality. This hurts both 试卷结构 (Beijing Q21 should be 新定义) and 创新与趋势 (no novel capstone) and 难度梯度 (the capstone is easier/more routine than Beijing's Q21).

Wait, let me re-read Paper 6's questions. Page 50-52: 1.(13分)三角 (2a sinB=√3 b) 2.(14分)数列 (等差, a3=5, S6=36) 3.(14分)立几 (P-ABCD) 4.(15分)概率 (竞赛, 方差最值) 5.(14分)解几 (抛物线 y²=4x) 6.(15分)导数 (e^x-ax-1, 含 (1+1/n)^n<e) So Paper 6's Q21 (their #6) is a 导数 problem, NOT a 新定义. This is a significant structural deviation — Beijing's 21题 is reliably a 新定义/创新 problem (集合/数列/数论 abstraction). Paper 6 lacks this entirely. So:

- 试卷结构: deduct → 7 (题型分值题量 OK but the 解答题 sequence deviates: no 新定义 capstone, and the 分值 are 13/14/14/15/14/15 which is slightly off Beijing's typical 13/14/13/15/15/15 or similar). Actually the bigger issue is content-structure (no 新定义). I'll give 试卷结构 7.

Hmm, but "试卷结构" per the rubric is "题型设置、分值分布、题量". The 题型 (multiple choice/fill/solving) and 题量 (10/5/6) and 分值 (40/25/85) all match. The absence of 新定义 is more a 创新/coverage issue than pure structure. But Beijing's solving-question TYPES (三角/立几/概率/解几/导数/新定义) are part of structure-expectation. I'll moderately deduct structure to 8 and heavily note the missing 新定义 in 创新.

Let me reconsider. The 6 solving questions: Paper 6 has 三角, 数列, 立几, 概率, 解几, 导数. It has 数列 (Q2) instead of... and 导数 as capstone instead of 新定义. Beijing typically has: 三角(16), 立几(17), 概率统计(18), 解几(19), 导数(20), 新定义(21). Paper 6 has 三角(16), 数列(17!), 立几(18), 概率(19), 解几(20), 导数(21). So Paper 6 swapped: it has a standalone 数列 big question AND uses 导数 as the capstone, with NO 新定义. This is a notable structural deviation from Beijing norms. Beijing rarely has 数列 as a major 解答 (数列 usually in 选填), and ALWAYS has 新定义 at 21.

So Paper 6:

- 试卷结构: 7 (题量/分值/题型大类 OK, but 解答题 content-sequence deviates: 数列 as big Q + no 新定义 capstone, atypical for Beijing). 7.
- 考点覆盖: 8 (covers all板块 including 数列 explicitly; but the 新定义/创新 abstraction板块 absent). 8.
- 难度梯度: 7 (capstone is a routine 导数+不等式, easier than Beijing's 新定义 21题; discrimination at the top is weaker; (1+1/n)^n<e is a classic, low novelty). 7.
- 命题质量: 9 (error-free, all rigorous). High.
- 创新与趋势: 5 (most conventional paper; routine problem types throughout; no contextualization to speak of; no 新定义; classic textbook problems; (1+1/n)^n<e is decades-old). Low innovation. 5. Total: 7+8+7+9+5 = 36/50.

Hmm interesting, Paper 6 ties Paper 3 at 36 but for opposite reasons (Paper 6: clean but unoriginal/structurally off; Paper 3: original-ish but has errors).

Wait, I should double-check Paper 6's structure claim. Let me recount its 解答题. Actually, having a 数列 解答题 is not unheard of, and some Beijing-style papers do include 数列 as a big question. But the ABSENCE of 新定义 at Q21 is the real deviation. Beijing 2021-2025 Q21 were all 新定义/创新 (e.g., 2021 数论, 2022 数表, 2023 数列新定义, 2024 集合/数列, 2025 similar). So a predicted Beijing paper without a 新定义 Q21 is missing the signature feature. Paper 6's 导数 capstone (e^x-ax-1 → (1+1/n)^n<e) is a fine problem but belongs at Q20, not as the Q21 capstone. This is a real flaw for a "Beijing predicted paper."

OK so Paper 6 drops due to structure/innovation despite being error-free. Good — this differentiates it from Papers 1 and 8.

Paper 7:

- 试卷结构: 9 (proper Beijing structure, 新定义 capstone present)
- 考点覆盖: 9 (集合复数椭圆函数二项式条件三角向量数列; fill双曲线对数三角向量Collatz; solving三角/立几/概率/解几/导数/疏离子集新定义 — comprehensive). 9.
- 难度梯度: 8 (reasonable; Q15 Collatz, Q20 sophisticated, Q21 Fibonacci — good top-end; but Q8 muddled)
- 命题质量: 5 (Q17② sign error, Q20③ wrong range — two clear answer errors; Q16② inconsistency; Q8 contextualization muddle; Q19② under-justified relying on 极点极线 which is syllabus-edge). Multiple issues. 5.
- 创新与趋势: 8 (Collatz Q15 — very novel!, compute/charging contexts, Fibonacci capstone, 极点极线 in Q19; high 思维含量 and novelty, though Q8 context is muddled). 8. Total: 9+9+8+5+8 = 39/50.

Paper 8:

- 试卷结构: 9 (textbook Beijing; 新定义 capstone; clean; has the multi-statement Q15)
- 考点覆盖: 9 (集合复数抛物线二项式向量数列条件三角指数; fill二项式双曲线三角立体组合分段函数; solving三角/立几/概率/解几/导数/子集和新定义 — comprehensive). 9.
- 难度梯度: 8 (smooth; Q10 vector, Q15 multi-statement well-built, Q20 inequality, Q21 subset-sum with pigeonhole — solid but capstone slightly routine). 8. Actually the gradient is good. 9? The capstone (subset sums) is a bit easier than Paper 1's. I'll say 8.
- 命题质量: 9 (error-free; well-posed throughout; Q16 with infeasible option well-designed). High.
- 创新与趋势: 9 (BEST contextualization — battery decay Q9, drone composite-solid Q14, autonomous-driving Q18; authentic 趋势 alignment; subset-sum capstone is solid). 9. Total: 9+9+8+9+9 = 44/50.

So Paper 1: 44, Paper 8: 44. Tied! Let me break the tie.

Paper 1 (44): structure 9, coverage 9, gradient 9, quality 9, innovation 8. Paper 8 (44): structure 9, coverage 9, gradient 8, quality 9, innovation 9.

Difference: Paper 1 has +1 gradient (stronger capstone, m-完备列 harder/more elegant than subset-sums), Paper 8 has +1 innovation (better contextualization).

For Top 1, this is genuinely close. I'll pick... hmm. Given the stated 趋势 emphasis on 情境化, Paper 8's innovation edge aligns with what the evaluation prioritizes. But Paper 1's capstone is more intellectually substantial (the 思维含量 the trend also values).

Let me make a decision: I'll crown Paper 1 as Top 1, because its capstone (m-完备列, binary representation) is the more authentically Beijing and more elegant 新定义 problem — and the 新定义 capstone is the single most important quality differentiator for a Beijing math paper. The 思维含量 of Paper 1's capstone, combined with zero errors and strong all-around, makes it the best predicted Beijing paper. Paper 8 is an extremely close #2 and I'll note it's nearly tied (and is the top choice if 情境化/趋势 is the priority).

Actually, hold on. Let me reconsider the gradient score for Paper 8 vs Paper 1 capstone quality more carefully, because this is the crux.

Paper 1 Q21 (m-完备列): (I) check (1,2,4) is 7-完备 not 8-完备; (II) prove m≤2^k-1 and 15-完备 needs ≥4; (III) for 5 terms, max m=31, and prove the sequence must be 1,2,4,8,16. This is a beautiful, classic 新定义 problem about binary representation / subset sums with a uniqueness proof. Genuinely Beijing-caliber. High 思维含量.

Paper 8 Q21 (subset sums f(S)): (I) count subsets summing to 10; (II) pigeonhole for |S|=5; (III) max n=37 with greedy construction. Solid but more standard — counting + pigeonhole + greedy are well-trodden. Lower novelty than Paper 1's uniqueness proof.

So Paper 1's capstone is superior in 思维含量 and elegance. This justifies Paper 1 #1.

Final ranking by total:

1. Paper 1: 44 (Top 1)
2. Paper 8: 44 (essentially tied, #2 — best contextualization)
3. Paper 5: 43 (most sophisticated, but 1 dihedral error)
4. Paper 2: 40 (provisional, unverifiable)
5. Paper 4: 39 (1 distribution error)
6. Paper 7: 39 (2 errors, but novel)
7. Paper 3: 36 (broken Q9 + Q15 error) — 最不推荐
8. Paper 6: 36 (clean but conventional, no 新定义)

Hmm, Papers 4 and 7 tie at 39, and Papers 3 and 6 tie at 36. Let me reconsider to give a cleaner ranking or accept ties.

For the tie at 39 (Paper 4 vs 7): Paper 7 has more errors (2 vs 1) but more innovation (Collatz!); Paper 4 has 1 error but heavy garbling. I'll rank Paper 4 slightly above Paper 7 (fewer errors) → Paper 4 #5, Paper 7 #6. Or keep tied. Let me adjust: Paper 4 quality 6, Paper 7 quality 5; Paper 4 innovation 8, Paper 7 innovation 8. Paper 4: 9+8+8+6+8=39. Paper 7: 9+9+8+5+8=39. Tied. I'll note Paper 4 edges on fewer errors, Paper 7 on coverage/novelty. Fine to present as near-tied.

For tie at 36 (Paper 3 vs 6): Paper 3 has errors (incl. broken Q9), Paper 6 is clean but conventional/structurally-off. For 最不推荐, Paper 3's broken Q9 (unsolvable) is the more serious defect for actual use. So Paper 3 = 最不推荐. Paper 6, while unexciting, is at least entirely correct and usable. So I'd rank Paper 6 slightly above Paper 3 in "recommendability" despite equal totals — because correctness/usability matters more than novelty for an exam. Let me reflect this: actually for 命题质量 Paper 6 (9) >> Paper 3 (4), but Paper 3 beats Paper 6 on structure (9 vs 7), gradient (7 vs 7), innovation (7 vs 5), coverage (9 vs 8). Net tie at 36. But for "最不推荐," the broken problem in Paper 3 is disqualifying in a way that Paper 6's blandness is not. So 最不推荐 = Paper 3 (a usable exam can't have an unsolvable problem). I'll explain this nuance.

Actually, let me reconsider Paper 3's total. Q9 being BROKEN (no correct answer) is worse than I've scored. A broken problem in an exam is severe. Let me drop Paper 3's命题质量 to 4 (already there) — that reflects it. Total 36. And Paper 6 at 36. I'll declare Paper 3 最不推荐 due to the unsolvable Q9 + Q15 error (errors are worse than blandness for an exam's usability).

Hold on, let me reconsider whether I've been too harsh or lenient anywhere, and re-verify the two most consequential error claims (Paper 3 Q9, Paper 4 Q18) since they drive the rankings.

Paper 3 Q9 re-verification: "e^x − x − a = 0 有且仅有一个实根". g(x)=e^x-x-a. g'(x)=e^x-1, zero at x=0, min g(0)=1-a. g→+∞ as x→±∞.

- a<1: min>0, 0 roots.
- a=1: min=0, 1 root.
- a>1: min<0, 2 roots. Exactly one root ⟺ a=1. Options A(0,1) B[1,∞) C(-∞,1] D(R). Correct answer {1} not present. Answer key says B and reasons "min≥0 ⟺ a≥1" (backwards: min=1-a≥0 ⟺ a≤1). CONFIRMED: broken problem + wrong/contradictory solution. ✓ My claim holds.

Paper 4 Q18 re-verification: Y1~B(3,2/3), Y2~B(3,1/2), X=Y1+Y2. Answer claims P(X=1)=7/72, P(X=2)=19/72. I computed P(X=1)=9/216=1/24=3/72, P(X=2)=33/216=11/72. Answer's total: 1/216+7/72+19/72+7/24+11/36+1/6+1/27. Convert to /216: 1+21+57+63+66+36+8=252, /216=7/6≠1. CONFIRMED: distribution wrong, doesn't sum to 1. ✓ My claim holds.

Paper 5 Q17① re-verification: done above, correct |cos|=1/2 (actual -1/2), answer √2/2. CONFIRMED. ✓

Paper 7 Q20③ re-verification: f(x)=xe^x-ax², f(x)≥x for x≥0, a∈R. For x>0: a≤(e^x-1)/x, inf=1, and a≤0 trivially works. So a≤1, range (-∞,1]. Answer (0,1] wrongly excludes a≤0. CONFIRMED. ✓

Paper 7 Q17② re-verification: dihedral P-BD-C, computed actual cos=-√3/3 (obtuse), answer √3/3. CONFIRMED sign error. ✓

Good, my key error claims hold.

Now, let me reconsider Paper 1's coverage — does it lack 统计 (statistics)? Its Q18 is probability (分布列+期望+决策), which is 概率 not really 描述统计. Beijing usually has a 概率统计 problem at 18 which can be either. Paper 1's is fine (probability with decision-making). Coverage 9 stands. It lacks an explicit 圆 (circle) problem in 选填, but that's minor (not every Beijing paper has 圆). 9 is fine.

Let me also sanity check I'm not missing errors in Papers 1, 6, 8 (the "clean" ones), since calling them error-free is a strong claim.

Paper 1: re-verified selection (all correct), fill (all correct), Q16-21 (all correct). The Q16 redundancy (conditions 1&2 → same triangle) is a design note, not an error. Confident: error-free.

Paper 6: re-verified all. Q7 pyramid volume 4√2/3 ✓, Q19 variance max 3/4 ✓, Q20 focal chord min 4 ✓, Q21 (1+1/n)^n<e ✓. Confident: error-free. (Its issue is structural — no 新定义 capstone, conventional.)

Paper 8: re-verified all. Q14 surface area 28 ✓, Q17 dihedral √30/6 ✓ (with correct sign — I verified it's acute), Q21 subset sums n=37 ✓. Confident: error-free.

Good.

One more consideration: the prompt says "6维度" but lists 5. I'll note this discrepancy briefly and proceed with the 5 named dimensions (试卷结构, 考点覆盖, 难度梯度, 命题质量, 创新与趋势), computing total out of 50. I'll mention the 5-vs-6 thing once so the user knows I noticed, and offer that if they intended a 6th dimension (e.g., a separate 总体/可用性), I can add it.

Now formatting. The user's writing preferences (Chinese): avoid 破折号 (em dash), use Chinese quotes ""'', avoid colons (use commas) except direct quotes, avoid "不是X而是X". Also the system wants minimal formatting but a table is explicitly requested. I'll write in Chinese (the paper and prompt are Chinese, user is Chinese-language journalist).

I need to be careful about colons — avoid them. For scores I'll write like "试卷结构 9 / 考点覆盖 9..." or in prose "结构9分，覆盖9分". The table is fine (no colons in tables). For the per-paper sections, I'll use a heading like "试卷一" then the scores then commentary. Since the system says minimize formatting/headers but the user asked for structured逐卷 output with scores + table + recommendation, some structure is warranted (the user explicitly wants it). I'll use bold paper labels and a table, keeping it clean. Actually the tone_and_formatting says use formatting when "the content is multifaceted enough that they're essential for clarity" and when asked. An 8-paper evaluation with scores per dimension + a matrix table + ranking genuinely needs structure. I'll use minimal headers (paper names) and the requested table.

Hmm, but I should avoid over-formatting. Let me structure as: brief intro (noting the 5-vs-6 dimension thing + that some papers had OCR garbling), then 逐卷 (each paper: a one-line score summary + 2-3 sentence commentary), then the summary table with totals/ranking, then Top 1 + 最不推荐. I'll avoid colons throughout (challenging but doable), avoid em-dashes, use Chinese punctuation.

Wait — avoiding colons is going to be quite hard in a scored evaluation and might make it read awkwardly. Let me reconsider. The user's memory rule "写作中除直接引语外，避免使用冒号（：），用逗号替代" is a real stated preference. I'll honor it as best I can — use commas or restructure. For score lines I can do "结构9，覆盖9，梯度9，质量9，创新8" (commas, no colons). For the table, columns handle it. OK doable.

Also "避免使用'不是XX而是XX'句式" — I'll avoid that construction.

Let me also decide: inline vs file. This is a long analytical evaluation. The user is likely on mobile. A very long inline response is somewhat hard on mobile but this is analysis they'll read and reference, not a publishable artifact. The memory says 文章 delivery in md, but this is an evaluation/分析, not a 文章 for publication. I'll keep it inline. It'll be long but that's inherent to the task (8 papers). I could offer a md file at the end if they want it for reference. Actually, given the length and that they might want to keep/share this evaluation, offering a markdown file at the end is reasonable. But I won't create it unprompted; I'll offer.

Hmm, actually, reconsider: the output has a lot of structure (8 papers × commentary + a matrix table + recommendation). This is substantial enough that it's borderline "report." But it's fundamentally an analysis/evaluation the user requested to read in-conversation. I'll do it inline. If it's very long, that's fine — they asked for thoroughness.

Let me reconsider length management. I'll be concise per paper (the user asked for "2-3句核心点评" per paper, plus scores). I should NOT dump all my verification work; I'll surface the key errors I found (with 题号) and the headline judgment. Keep each paper tight. The table consolidates scores. Recommendation section explains Top 1 and 最不推荐.

I want to make sure I cite specific 题号 for errors (the user explicitly asked). Key ones to flag:

- Paper 3: Q9 (broken/no valid option + contradictory solution), Q15 (② wrongly included; should be ①③④)
- Paper 4: Q18 (distribution doesn't sum to 1; P(X=1), P(X=2) wrong)
- Paper 5: Q17 条件① (dihedral; √2/2 wrong, should be |1/2|)
- Paper 7: Q17(II) (sign; should be -√3/3), Q20(III) (range; should be (-∞,1] not (0,1]), Q16② (a²=2 vs a=2 inconsistency)
- Paper 1: note Q16 redundancy (not error)
- Paper 6: note missing 新定义 capstone (structural)

Let me also reconsider — should I double check Paper 3 Q7 (interval) is worth mentioning? It's a borderline option-design issue (both (-∞,1] and (-∞,1) present). Minor. I'll mention briefly under Paper 3.

Also Paper 2 — be transparent it's largely unverifiable due to OCR garbling; score provisionally.

Let me also reconsider whether to mention the "Mavis"/"AI生成" residual labels. The PDF explicitly says "请勿猜测出题模型" and "个别试卷页眉/页脚可能残留模型标识". The user (as evaluator) presumably wants a blind eval. I should NOT speculate about which model made which paper. I'll avoid commenting on the residual labels entirely, or just neutrally note I'm ignoring them per the blind-eval instruction. Best to just not bring it up and evaluate on content. I won't mention Mavis or AI生成 labels.

Now let me reconsider the dimension count issue once more and how to present. I'll say upfront something like: the rubric lists 5 评分维度 (试卷结构/考点覆盖/难度梯度/命题质量/创新与趋势) though the instructions mention 6; I'll score on these 5 (满分50), and if a 6th was intended I can add it. Brief.

Let me also reconsider: is there a 6th dimension I'm missing in the table? Re-reading the prompt's table: header "维度 | 说明", then 5 rows. Definitely 5. The "6个维度" is an error in the prompt. I'll note and proceed with 5.

Let me now also reconsider the overall difficulty assessment relative to real Beijing. Real Beijing 2021-2025 is medium-difficulty with a hard 新定义 capstone and 1-2 hard 选填. Most of these papers match. Papers 1, 5, 7, 8 have proper hard capstones; Paper 6 lacks it; Paper 3's capstone is hard but the paper has the broken Q9.

OK, I think I have enough to write a thorough, accurate evaluation. Let me also make sure to be appropriately confident but humble — I verified the math myself, so I can state errors with confidence, but I'll acknowledge the OCR limitation for Papers 2, 4, 7 where it applies.

Let me reconsider scores once more for consistency and write them down:

Paper 1: 结构9 覆盖9 梯度9 质量9 创新8 = 44 Paper 2: 结构9 覆盖8 梯度8 质量7* 创新8 = 40 (*provisional, unverifiable) Paper 3: 结构9 覆盖9 梯度7 质量4 创新7 = 36 Paper 4: 结构9 覆盖8 梯度8 质量6 创新8 = 39 Paper 5: 结构9 覆盖9 梯度9 质量7 创新9 = 43 Paper 6: 结构7 覆盖8 梯度7 质量9 创新5 = 36 Paper 7: 结构9 覆盖9 梯度8 质量5 创新8 = 39 Paper 8: 结构9 覆盖9 梯度8 质量9 创新9 = 44

Ranking:

1. 试卷一 44 / 试卷八 44 (tie at top)
2. 试卷五 43
3. 试卷二 40 (provisional)
4. 试卷四 39 / 试卷七 39 (tie)
5. 试卷三 36 / 试卷六 36 (tie)

Top 1: 试卷一 (with 试卷八 essentially tied; pick 试卷一 for superior 新定义 capstone). 最不推荐: 试卷三 (broken Q9 + Q15 error).

Hmm, the ties are a bit awkward for a "排名". Let me see if I can justify small adjustments to break ties cleanly, while staying honest.

试卷一 vs 试卷八: I'll keep both at 44 but rank 试卷一 #1 (capstone), 试卷八 #2. Acceptable to have them as 44/44 with 试卷一 declared Top 1 on tiebreak (capstone 思维含量).

试卷四 vs 试卷七 (both 39): 试卷四 has fewer errors (1 vs 2) but 试卷七 has higher coverage/novelty. I could nudge 试卷四 to質量6→ keep, and 试卷七 quality 5. They're 39 each. I'll rank 试卷四 #5, 试卷七 #6, noting 试卷四 is cleaner (fewer errors) while 试卷七 is more ambitious but error-prone. Or just present as tied. I'll give a slight edge to 试卷四 (#5) over 试卷七 (#6) on grounds of fewer errors, but note closeness.

Actually, to break the 39 tie more principledly: 试卷七 has 2 confirmed errors + 1 inconsistency + muddled context, vs 试卷四's 1 error + garbling. On 命题质量 试卷四 (6) > 试卷七 (5). For an exam, fewer errors → more usable. So 试卷四 ranks above 试卷七. I'll set 试卷四 = #5, 试卷七 = #6.

试卷三 vs 试卷六 (both 36): For ranking, since 试卷三 is 最不推荐 (broken problem), I'll rank 试卷六 #7, 试卷三 #8 (last). Justification: 试卷六, though conventional and missing 新定义, is entirely correct and usable; 试卷三 has an unsolvable problem making it the least usable. So 试卷六 #7, 试卷三 #8 (最不推荐).

Final ranking:

1. 试卷一 (44) — Top 1
2. 试卷八 (44)
3. 试卷五 (43)
4. 试卷二 (40, provisional)
5. 试卷四 (39)
6. 试卷七 (39)
7. 试卷六 (36)
8. 试卷三 (36) — 最不推荐

This is clean and defensible. Good.

Now, let me reconsider whether Paper 2's provisional 40 should rank above Paper 4/7's verified 39. Since Paper 2 is unverifiable, its 40 is uncertain — it could be higher or lower if I could check. Ranking it #4 (above 4 and 7) is reasonable given its structure/coverage/innovation are solid where visible and I found no errors in the legible parts. But I should flag the provisionality. Alternatively I could decline to rank it precisely. I'll rank it #4 with an explicit asterisk/caveat that the score is provisional pending legible source. That's honest.

Alright. Let me also prepare the commentary for each paper (2-3 sentences, 优点+不足, with 题号 for errors). In Chinese, avoiding colons/em-dashes/不是X而是X.

Let me draft the per-paper commentary:

试卷一 (44): 优点 结构与北京卷高度吻合，21题"m-完备列"是一道关于二进制表示与子集和的新定义压轴，分层清晰且含唯一性证明，思维含量足；选填到解答梯度平滑，全卷未发现数学错误。 不足 16题"条件一(B为锐角)"与"条件二(c=4)"最终导向同一个三角形(B=π/3、C=π/2)，两个条件区分度不够，略显冗余。情境化题目数量中等。

试卷二 (40, provisional): 说明 该卷PDF抽取后公式大面积缺失，题干基本不可读，以下评分主要依据可辨认的答案与解析，属临时判断。 优点 解答题序列(三角/立几/概率/解几/导数/独立集斐波那契)符合北京卷，答案解析在可读处自洽，21题独立集计数与递推是经典好题。 不足 因原文乱码，命题严谨性无法完整核验，建议提供清晰版后复评。

试卷三 (36, 最不推荐): 不足(重要) 第9题"e^x−x−a=0有且仅有一个实根"存在硬伤，正确答案应为a=1(唯一)，而四个选项中无此项，给出的答案B=[1,∞)错误，且解析"最小值≥0⟺a≥1"本身自相矛盾(最小值1−a≥0应得a≤1)；第15题答案①②③④有误，命题②"f(x)的最大值为1"为假(x>0时x²−2x→+∞无最大值)，正确应为①③④。 其他 第7题选项同时出现(−∞,1]与(−∞,1)，单调区间端点设计有歧义；21题(3)必要性证明偏粗略。 优点 覆盖面广(含圆)，Rp数列压轴有新意，结构规范。

试卷四 (39): 说明 原文亦有较多乱码，仅就可读部分核验。 不足 第18题X的分布列有误，P(X=1)与P(X=2)计算错误，全表概率之和为7/6而非1(正确P(X=1)=1/24、P(X=2)=11/72)；期望EX=7/2用期望线性性算出，恰好正确。 优点 电池能量密度(第9题)等情境化题目得体，21题"好排列"用捆绑法与容斥求解干净，其余可核验部分正确。

试卷五 (43): 优点 全卷思维含量最高之一，21题"可约零序列"本质是GF(2)上的循环线性方程组，结论(偶数个1⟺可约)优雅且对任意n成立；20题用极值点偏移构造F(x)证明x₁+x₂>2e^{a−1}严谨；情境化(算力成本C(x)=kx·log₂x、雨水收集器)与机器人测试题设计上佳。 不足 第17题条件①(F为PC中点)的二面角E−BF−C解答有错，误将平面BFC当作底面取法向量(0,0,1)，所得√2/2不对，正确余弦值的绝对值为1/2(实际为钝角−1/2)；条件②无误。

试卷六 (36): 不足(结构) 缺少北京卷标志性的新定义压轴，第21题用了一道常规导数题(e^x−ax−1并由此证(1+1/n)^n<e)，且第17题为独立的数列大题，解答题大类配置偏离北京卷惯例；情境化几乎缺位，整体偏套路化、创新最弱。 优点 全卷零错误、推演规范，复数/三角/立几/概率/解几/导数等基础板块覆盖扎实，可作为常规练习卷。

试卷七 (39): 说明 原文有乱码，就可读部分核验。 不足 第17题(II)二面角P−BD−C符号有误，该二面角为钝角，余弦值应为−√3/3而非√3/3；第20题(III)结论有误，f(x)=xe^x−ax²、a∈R下应为a∈(−∞,1]，解析凭空引入"a>0(题设)"得(0,1]是错的；第16题条件②按a=2应得a²=4，而解析按a²=2计算，bc与面积随之有出入(疑似笔误或漏写根号)；第8题情境(覆盖率/渗透率)题干与解法对不上，设定混乱；第19题(II)直接套用极点极线、推导未完成，越界且不完整。 优点 第15题Collatz型数列、21题"疏离子集"斐波那契压轴很有新意，思维含量高。

试卷八 (44): 优点 情境化做得最好，电池衰减(第9题)、低空经济无人机组合体(第14题)、自动驾驶算法可靠性(第18题)紧扣"情境化、减少机械计算"的趋势；结构规范、含新定义压轴与多结论第15题；全卷未发现数学错误。 不足 21题"子集和"压轴用抽屉原理与贪心构造求n=37，扎实但偏常规，思维含量略逊于试卷一的二进制唯一性证明；难度顶端区分度稍弱。

Now the table. Columns: 试卷 | 结构 | 覆盖 | 梯度 | 质量 | 创新 | 总分 | 排名. I'll order by 试卷 number or by rank? The user wants "8份试卷×6维度的分数矩阵，附总分排名". I'll present in 试卷 order (一..八) with totals and a rank column, then a one-line ranking summary. Or order by rank. I'll do 试卷 order with rank column, plus a ranking line. Actually clearer to also give the ranked list. Let me present the matrix in 试卷 order, then below it the ranking.

Let me build the table (markdown):

| 试卷 | 结构 | 覆盖 | 梯度 | 质量 | 创新 | 总分(50) | 排名 |
| ---- | ---- | ---- | ---- | ---- | ---- | -------- | ---- |
| 一   | 9    | 9    | 9    | 9    | 8    | 44       | 1    |
| 二*  | 9    | 8    | 8    | 7    | 8    | 40       | 4    |
| 三   | 9    | 9    | 7    | 4    | 7    | 36       | 8    |
| 四*  | 9    | 8    | 8    | 6    | 8    | 39       | 5    |
| 五   | 9    | 9    | 9    | 7    | 9    | 43       | 3    |
| 六   | 7    | 8    | 7    | 9    | 5    | 36       | 7    |
| 七*  | 9    | 9    | 8    | 5    | 8    | 39       | 6    |
| 八   | 9    | 9    | 8    | 9    | 9    | 44       | 2    |

*标注的试卷因原文乱码，评分为临时判断。

Wait, I marked 二, 四, 七 with asterisk for OCR garbling. Paper 4 and 7 I could verify a fair amount (found specific errors), so they're not as "unverifiable" as Paper 2. Let me only assterisk Paper 2 as truly provisional, and note Papers 4/7 had partial garbling but I verified key parts. Actually 4 and 7 had garbled problem statements but readable answer keys where I found errors. I'll asterisk all three with a note distinguishing severity. Or just note in prose. Let me keep the table clean and put the OCR caveat in prose under it. I'll asterisk 二 only (truly unverifiable), and mention 四/七 had partial garbling in their commentary.

Hmm, but I gave 二 a 40 which ranks #4, above verified papers. That might overrank an unverifiable paper. Let me reconsider — given I can't verify 二's correctness, awarding it 质量7 is generous. If it has hidden errors, it'd drop. To be safe and honest, maybe I should rank it lower or explicitly mark its rank as uncertain. I'll keep 40/#4 but flag clearly that it's provisional and could move. Acceptable with transparency.

Actually, you know, let me reconsider Paper 2's 质量 score. I literally cannot verify the problems. Giving 7 assumes competence. But the legible answer-key logic IS coherent (the explanations, where readable, are sound). And I found no errors in legible parts. 7 with a caveat is defensible (not 9, because unverified; not low, because no errors found and structure/logic sound). OK.

Now the Top 1 and 最不推荐 section.

Top 1: 试卷一. 理由: 全卷零数学错误；结构与北京卷高度一致(10选4+5填5+6解，16三角/17立几/18概率/19解几/20导数/21新定义)；21题"m-完备列"是最具北京味、最优雅的新定义压轴(二进制表示+唯一性证明)，思维含量与区分度俱佳；难度梯度平滑、覆盖全面。试卷八几乎并列(44分)，情境化甚至更出色(无人机/电池/自动驾驶)、同样零错误，若以"情境化"为第一优先可选试卷八；我把第一名给试卷一，主要因其压轴的思维深度更胜一筹(子集和+抽屉/贪心相对常规)。

最不推荐: 试卷三. 理由: 第9题是一道无解的废题(正确答案a=1不在选项内，且所给答案与解析自相矛盾)，对一份要投入实战的卷子是致命的；叠加第15题答案错误(误收命题②)，命题质量明显失守。试卷七问题也不少(两处答案错误+情境混乱)，可视为次差；但试卷三因含一道根本无法作答的题而排在最后。

Let me make sure I avoid colons. I'll rewrite avoiding "：". Use commas/。 Let me be careful in final text.

Also avoid em-dash "——". I used some "—" in my draft thinking; remove in final. Use commas or parentheses.

Let me also reconsider: the user is a tech journalist, and these are AI-generated papers. An interesting observation worth a brief note: many papers inject AI/tech情境 (机器学习训练误差、算力成本、自动驾驶、电池、充电桩、机器人测试、增长模型). This is a notable pattern (the AI models seem to favor AI/tech contexts). I could add a one-line observation at the end since Heck would find it relevant. But I should keep focus on the eval. Maybe one sentence at the very end as a light observation. Actually, it's tangential to the grading task; I'll add a brief closing observation since it's genuinely interesting and relevant to the user's beat, but keep it to one or two sentences. Or skip to stay focused. I'll add a short note — it's the kind of insight a tech journalist evaluating AI outputs would appreciate, and it's accurate from the content. One sentence.

Let me also offer the markdown file at the end (optional), since this is long and they might want to keep/share it. Brief offer.

Let me now also double check a couple more potential errors I might've glossed, to be safe in claiming the clean papers are clean and not miss errors in others.

Paper 5 Q16 — let me verify condition③ gives valid triangle. area=√3, a=2, B=π/3 → c=2, b=2 (equilateral). All sides 2, area=√3·4/4=√3 ✓. Good.

Paper 8 Q9 — battery. e^{-2k}=0.9, k=-ln0.9/2≈0.0525. t=-ln0.7/k≈0.357/0.0525≈6.8→7年. ✓. Answer C. Good.

Paper 6 Q4 — sinα=3/5 second quadrant, tanα=-3/4. ✓ A.

Paper 1 Q5 binomial coeff x² = 60. ✓.

OK I'm confident. Let me also reconsider Paper 3 Q15 statement ④ to make sure I correctly excluded it / included it. Answer is ①②③④ (all). I claimed ② is false (no max). Let me re-verify ④: "f(x)在(−∞,−1)上单调递增". For x<0, f(x)=-x²-2x (from odd extension: f(x)=-f(-x)=-((-x)²-2(-x))=-(x²+2x)=-x²-2x). f'(x)=-2x-2. On (−∞,−1): x<-1, -2x>2, -2x-2>0, so f'>0, increasing. ④ true. So correct answer ①③④ (② false, ①③④ true). Paper says ①②③④. Error is including ②. ✓ Confirmed (my claim: should be ①③④).

Wait, I should double check ③ "极小值为−1". For the odd function: x>0 part x²-2x has local min at x=1 (f=-1). x<0 part -x²-2x has local max at x=-1 (f=1). So 极小值 (local min) is -1 (at x=1). ③ true. And ① three zeros (0, ±2... wait x=2 and x=-2 and 0). zeros: x>0: x²-2x=0→x=2 (and 0 but 0 is boundary). x<0: -x²-2x=0→x(-x-2)=0→x=0 or x=-2, so x=-2. Plus f(0)=0. So zeros at -2, 0, 2. Three. ① true. So ①③④ true, ② false. Confirmed.

Good. Now writing the final response in Chinese. Let me keep it organized but not bloated. I'll lead with a 1-2 sentence framing (note the 5 dimensions + OCR caveat), then 逐卷, then table, then Top1/最不推荐, then a one-line observation + offer.

Length check: 8 papers × ~3 sentences + table + recommendation. That's substantial but appropriate. Let me write tightly.

On the colon avoidance: section labels like "试卷一（44/50）" then prose. For "优点"/"不足" I'll use them as inline lead-ins followed by comma or just sentence, avoiding colon. E.g., "优点，结构..." reads oddly. Better, "优点方面，结构...；不足方面，..." or just write flowing prose without 优点/不足 labels and colons. Let me write each paper as 2-3 flowing sentences mentioning strengths and weaknesses, no colons. That's cleanest and honors the no-colon rule.

Actually using "优点，" with comma is acceptable-ish but a bit unusual. Let me just write natural prose. For errors I'll clearly cite 题号.

Let me finalize. I'll write the response now.

One more: the system says respond in the language the user uses. The prompt is in Chinese. So respond in Chinese. Confirmed: Chinese.

Let me write it. I'll use a markdown table (allowed, requested). I'll keep headers minimal — maybe just bold paper labels rather than ## headers to reduce formatting heaviness, but for an 8-section structured eval, light headers/bold are fine and aid clarity. I'll use bold paper names.

Let me write.

Final structure:

- Short intro (2-3 sentences): 5 dimensions noted (6 in prompt), OCR caveat for 二/四/七.
- 逐卷 (一 to 八): bold label + score line + 2-3 sentence commentary with 题号 for errors.
- 汇总表格 (matrix + total + rank).
- Top 1 + 最不推荐 (with reasons).
- Closing one-liner (AI/tech情境 observation) + offer md file.

Writing now. Keep tight. Avoid 冒号、破折号、"不是X而是X"。Use Chinese quotes.

Actually for score lines, to avoid colon, I'll write: "结构9、覆盖9、梯度9、质量9、创新8，合计44。" Good, uses 顿号 and no colon.

Let me make sure each error citation is precise and I don't overclaim. For Paper 7 Q16②, I'll phrase it as "疑似" since OCR-ambiguous. For the clear ones (Paper 3 Q9/Q15, Paper 4 Q18, Paper 5 Q17①, Paper 7 Q17②/Q20③), state confidently.

Writing final response.先说明一点，题目给出的评分维度表实际只列了 5 项（试卷结构、考点覆盖、难度梯度、命题质量、创新与趋势），文字里却写"6 个维度"。我按这 5 项各 1–10 分、满分 50 来打。若你本意是有第 6 项（比如单列"整体可用性"），告诉我我再补。

另外，试卷二、四、七的 PDF 抽取后公式大面积缺失，题干部分不可读。试卷二几乎只能依答案与解析判断，属临时评分；试卷四、七题干虽乱，但答案解析可读，我在可核验处做了验算并指出了具体错误。下面每卷的数学错误我都逐题算过。

**试卷一**　结构9、覆盖9、梯度9、质量9、创新8，合计44。 全卷未发现数学错误。结构与北京卷高度吻合，21 题"m-完备列"是关于二进制表示与子集和的新定义压轴，含 1、2、4、8、16 唯一性证明，分层清晰、思维含量足，最具北京味。唯一可挑的是 16 题，"条件一（B 为锐角）"与"条件二（c=4）"最终都导向同一个三角形（B=π/3、C=π/2），两条件区分度不够，略冗余；情境化数量中等。

**试卷二**　结构9、覆盖8、梯度8、质量7、创新8，合计40（临时）。 原文乱码严重，以下基于可辨认的答案解析。解答序列（三角/立几/概率/解几/导数/独立集与斐波那契）符合北京卷，可读处解析自洽，21 题独立集计数与递推是经典好题。命题严谨性无法完整核验，建议给清晰版后复评，排名带不确定性。

**试卷三**　结构9、覆盖9、梯度7、质量4、创新7，合计36。 有两处实打实的问题。第 9 题"e^x−x−a=0 有且仅有一个实根"是废题，正确答案应为 a=1（唯一），四个选项中根本没有这一项，所给答案 B=[1,+∞) 错误，而且解析"最小值≥0 等价于 a≥1"本身矛盾（最小值 1−a≥0 应得 a≤1）。第 15 题答案①②③④有误，命题②"f(x) 的最大值为 1"为假（x>0 时 x²−2x→+∞，无最大值），正确应为①③④。此外第 7 题选项同时出现 (−∞,1] 与 (−∞,1)，单调区间端点设计有歧义；21 题(3) 必要性证明偏粗。优点是覆盖广（含圆）、Rp 数列压轴有新意、结构规范。

**试卷四**　结构9、覆盖8、梯度8、质量6、创新8，合计39。 原文有乱码，仅核验可读部分。第 18 题 X 的分布列有误，P(X=1) 与 P(X=2) 算错，全表概率之和为 7/6 而非 1（正确应为 P(X=1)=1/24、P(X=2)=11/72）；期望 EX=7/2 因用了期望线性性，恰好仍正确。电池能量密度（第 9 题）等情境题得体，21 题"好排列"用捆绑法加容斥求解干净，其余可核验部分无误。

**试卷五**　结构9、覆盖9、梯度9、质量7、创新9，合计43。 思维含量最高的一份。21 题"可约零序列"本质是 GF(2) 上的循环线性方程组，结论"1 的个数为偶数等价于可约、且对任意 n 成立"优雅；20 题用极值点偏移构造 F(x) 证明 x₁+x₂>2e^{a−1} 严谨；情境化（算力成本 C(x)=kx·log₂x、雨水收集器、机器人测试并比较优化前后期望）设计上佳。失分在第 17 题条件①（F 为 PC 中点）的二面角 E−BF−C，解析误把平面 BFC 当作底面取法向量 (0,0,1)，所得 √2/2 不对，正确余弦值绝对值为 1/2（实际是钝角 −1/2）；条件②无误。

**试卷六**　结构7、覆盖8、梯度7、质量9、创新5，合计36。 全卷零错误、推演规范，是可靠的常规练习卷。但它缺少北京卷标志性的新定义压轴，第 21 题换成了一道常规导数题（e^x−ax−1 并由此证 (1+1/n)ⁿ<e），且第 17 题是独立的数列大题，解答题大类配置偏离北京卷惯例；情境化几乎缺位，整体最套路化、创新最弱，顶端区分度不足。

**试卷七**　结构9、覆盖9、梯度8、质量5、创新8，合计39。 原文有乱码，就可读部分核验，问题较多。第 17 题(II) 二面角 P−BD−C 符号错了，该二面角为钝角，余弦值应为 −√3/3 而非 √3/3。第 20 题(III) 结论错误，在 f(x)=xe^x−ax²、a∈R 下应为 a∈(−∞,1]，解析凭空加了"a>0（题设）"得到 (0,1] 是错的。第 16 题条件②按 a=2 应有 a²=4，解析却按 a²=2 计算，bc 与面积随之出入（疑似漏写根号或笔误）。第 8 题（覆盖率/渗透率）题干与解法对不上，设定混乱。第 19 题(II) 直接套极点极线、推导没走完，越界且不完整。亮点是第 15 题 Collatz 型数列、21 题"疏离子集"斐波那契压轴很有新意。

**试卷八**　结构9、覆盖9、梯度8、质量9、创新9，合计44。 情境化做得最好，电池衰减（第 9 题）、低空经济无人机组合体（第 14 题）、自动驾驶算法可靠性（第 18 题）都紧扣"情境化、减少机械计算"的趋势；结构规范、含新定义压轴与多结论第 15 题；全卷未发现数学错误。不足是 21 题"子集和"压轴用抽屉原理加贪心构造求 n=37，扎实但偏常规，思维深度略逊于试卷一的二进制唯一性证明，顶端区分度稍弱。

**汇总矩阵与排名**

| 试卷 | 结构 | 覆盖 | 梯度 | 质量 | 创新 | 总分(50) | 排名 |
| ---- | ---- | ---- | ---- | ---- | ---- | -------- | ---- |
| 一   | 9    | 9    | 9    | 9    | 8    | 44       | 1    |
| 二＊ | 9    | 8    | 8    | 7    | 8    | 40       | 4    |
| 三   | 9    | 9    | 7    | 4    | 7    | 36       | 8    |
| 四   | 9    | 8    | 8    | 6    | 8    | 39       | 5    |
| 五   | 9    | 9    | 9    | 7    | 9    | 43       | 3    |
| 六   | 7    | 8    | 7    | 9    | 5    | 36       | 7    |
| 七   | 9    | 9    | 8    | 5    | 8    | 39       | 6    |
| 八   | 9    | 9    | 8    | 9    | 9    | 44       | 2    |

排名顺序为 一 ＞ 八 ＞ 五 ＞ 二＊ ＞ 四 ＞ 七 ＞ 六 ＞ 三。带＊的试卷二为临时评分，清晰版到手后可能上下移动。试卷四与七同为 39 分，我把试卷四排前，因其只有一处错误、更接近可直接使用；试卷三、六同为 36 分，试卷六虽平庸但全对、可用，故排在试卷三之前。

**Top 1，试卷一。**　它零数学错误，结构与北京卷几乎一比一（10 选 4＋5 填 5＋6 解，16 三角、17 立几、18 概率、19 解几、20 导数、21 新定义），21 题压轴是最具北京味、最优雅的新定义题，二进制表示加唯一性证明，思维含量和区分度都到位，难度梯度平滑、覆盖全面。试卷八与它几乎并列（同 44 分），情境化甚至更强（无人机、电池、自动驾驶）、同样零错误，如果你把"情境化贴近趋势"放第一位，选试卷八完全成立。我把第一名给试卷一，主要因为它压轴的思维深度更胜一筹，子集和加抽屉、贪心相对常规。

**最不推荐，试卷三。**　第 9 题是一道无解的废题，正确答案 a=1 根本不在选项里，所给答案与解析还自相矛盾，这对一份要拿去实战的卷子是致命的；再叠加第 15 题答案错误（误收命题②），命题质量明显失守。试卷七问题同样不少（两处答案错误加情境混乱），可视为次差，但试卷三因为含一道根本无法作答的题，排在最后。

最后一点你大概会感兴趣，这八份卷子里 AI/科技情境出奇地密集，机器学习训练误差、算力成本、自动驾驶、电池衰减、充电桩、机器人测试、各种"增长模型"，几乎每份都往自己熟悉的领域里塞背景，这种取材偏好本身就挺值得一说。

需要的话我可以把这份评测整理成一个 md 文件方便你存档或转给编辑。