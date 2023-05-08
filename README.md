Download Link: https://assignmentchef.com/product/solved-ve475-introduction-to-cryptography-homework-7
<br>
<strong>Ex. 1 –</strong><em> Cramer-Shoup cryptosystem</em>

<ol>

 <li>Detail the construction of the Cramer-Shoup cryptosystem.</li>

 <li>Explain why this cryptosystem is secure even against adapative chosen ciphertext attacks (no formal proof is required, only some basic explanations).</li>

 <li>Compare this construction to the Elgamal cryptosystem (highlight the similarities and differences). <strong> 2 –</strong><em> Simple questions</em></li>

 <li>Let p be a prime and α be an integer such that p<strong> { </strong>α. Explain why h(x) ≡ α<sup>x</sup> mod p is not a good cryptographic hash function.</li>

 <li>Express ⌊2<sup>30</sup>√i⌋ for i = 2,3,5 and 10, in hexadecimal. Compare your results to the constants Ki, 0 ≤ i ≤ 79, in SHA-1.</li>

</ol>

<strong>Ex. 3 –</strong><em> Birthday paradox</em>

In this exercise we derive the approximation of the probability of having at least one match in a list of length r over n possible birthdays.

<ol>

 <li>Let f (x) = ln(1 − x) and g(x) = ln(1 − x) + x + x<sup>2</sup>. Study the functions f and g over [0, 1/2] and conclude that over this interval</li>

</ol>

−x − x<sup>2</sup> ≤ ln(1 − x) ≤ −x.

<ol start="2">

 <li>Prove that if r ≤ n/2 then</li>

</ol>




(r − 1)r         r3

______ −____ ≤

2n           3n<sup>2</sup>

(r − 1)r<sub>.</sub>

‘        n)≤ −______

2n




<ol start="3">

 <li>Let λ = r<sup>2</sup>/(2n), and suppose λ ≤ n/8. Prove that</li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="143">e−λec1/sqrtn ≤</td>

   <td width="437">jjj (1 −   where c1 = Iλ − (2λ)3/2 and c2 =‘               n)<sup>,</sup>      V2            3                    V2j=1</td>

  </tr>

 </tbody>

</table>




<ol start="4">

 <li>Prove that when n is large and λ is a constant less than n/8, then r−1~ ~</li>

</ol>

~ 1 − j ≈ e<sup>−λ</sup>.n

j=1




<strong>Ex. 4 –</strong><em> Birthday attack</em>

Suppose we observe 40 licence plates, each ending with a 3-digit number.

<ol>

 <li>What is the probability of seeing two plates ending with the same three digits?</li>

 <li>Assuming we have one ending with 123. What is the probability that one of the 40 license plates observed has the same 3 last digits?</li>

 <li>Explain how these results relate to how Alice overcomes the birthday attack in chapter 5.</li>

</ol>

<strong>Ex. 5 –</strong><em> Faster multiple modular exponentiation</em>

Let α,β, a, b and n be five integers. The most obvious strategy for compute α<sup>a</sup>β<sup>b</sup> mod n consists in using the modular exponentiation (Square and Multiply) algorithm (3.38) to compute α<sup>a</sup> mod n, and βb mod n and then multiply the results mod n.

<ol>

 <li>What is the time complexity of this method?</li>

 <li>Assuming the product αβ is known, rewrite the square and multiply algorithm, such that at most one multiplication is calculated at each iteration.</li>

 <li>Suppose a and b are l bits long; how many squaring and multiplications are necessary to compute α<sup>a</sup>β<sup>b</sup> mod n ?</li>

 <li>Implement the two strategies and compare their speed on large numbers.</li>

</ol>