<h1 id="c-tutorial">C-tutorial</h1>
<h1 id="what-is-c-">What is C?</h1>
<p> Actual ma vanna parda chai <code>C</code> vaneko chai general-purpose programming language ho.
 General-purpose vanne bitikai euta specialized or exact task lai navai wide range of application ma use garna milxa.
Jastai examples ko lagi:</p>
<ul>
<li>C Langauge: Yo chai mid level, general programming langauge ho, widely Opreating System, Compilers, ani aru system software haru develop garna lai use hunxa.</li>
<li>C++ : C++ chai object-oriented programming language ho based on C Langauge ani widely application development ma use hunxa particularly application jaslai chai high degree of performance ko jarurat hunxa.</li>
</ul>
<p>C langauge chai unix naam gareko Opreating System banauna lai develop gareko ho.</p>
<h1 id="why-c-langauge-learn-c-language-">Why C langauge (learn C Language)?</h1>
<ul>
<li>Yo chai world ko sab vhanda popular programming langauge ho.</li>
<li>Yedi C language ramrari bujyo vane aru programming haru bujna lai garo hudaina jastai: Java, C++, C#, etc, syntax haru milxa.</li>
<li>C langauge ko Compilation time ekdam chado xa aru programming langauge ko tulana maa.</li>
<li>C Langauge ekdamnai versatile langauge ho yo application sangai technology development ma use hunxa.</li>
</ul>
<h1 id="c-and-c-">C and C++</h1>
<p>C suru garna vhanda paila c ra c++ ko diffrence jann jaruri xa.</p>
<ul>
<li>C++ C ko extension aathwa bistarko rupp ma develop gariyeko thiyo, ra duitai language ko syntax dherai similar xa.</li>
<li>C ra C++ bich ko important diffrence vaneko chai C++ le  classes, object support garxa tara C le gardaina.</li>
</ul>
<h1 id="let-s-start">Let&#39;s Start</h1>
<p>So C suru garna vhanda paila hamlai euta text editor code lekhna lai ani arko tyo code lai translate garna lai c compiler.</p>
<ul>
<li>Text Editor: Notepad++, Vs Code, Dev C++ (editor + compiler yo best hunxa).</li>
<li>Compiler: gcc yesle chai C code lai translate garera computer le bujena langauge banauxa.</li>
<li>Basic programming ko lagi online compiler haru use garda ni hunxa jastai: <a href="https://www.onlinegdb.com/">GDB</a>, <a href="https://www.programiz.com/c-programming/online-compiler/">Programiz</a>, etc.</li>
</ul>
<h1 id="quickstart">Quickstart</h1>
<p>Aaba suru ma chai C programme ko basic structure bata suru garum.</p>
<ul>
<li>Paila compiler kholum ani euta naya file create garum <code>main.c</code>.
Tespaxi Hello World! print garney code lekhum:
```C
#include<stdio.h></li>
</ul>
<p>int main(){</p>
<pre><code>printf(<span class="hljs-string">"Hello World!);</span>
return <span class="hljs-number">0</span>;
</code></pre><p>}</p>
<pre><code>Mathi lekhiyeko C <span class="hljs-built_in">code</span> bujnu vayo ki nai? Bujnu vayo vane thikai xa, Bujnu vayena vane pani thikai xa aaba hami mathi ko <span class="hljs-built_in">code</span> lai tukra tukra parera bujna try garxum.

- Yo mathi <span class="hljs-built_in">code</span> lai maile jasari lekhnus tapai le choose garna vako compiler ma lekhnus. 
` Maile chai Dev C++ <span class="hljs-keyword">use</span> garey:

![image](https:<span class="hljs-comment">//user-images.githubusercontent.com/67673221/209978594-896b28be-18e1-4570-8e91-6bb330173441.png)</span>



So aaba yo <span class="hljs-built_in">code</span> lai <span class="hljs-keyword">run</span> gari herum hai ta <span class="hljs-keyword">output</span> aauxa ki aaudain raixa vanera.
`Note: Tapaile <span class="hljs-built_in">code</span> lai <span class="hljs-keyword">run</span> garna vhanda paila <span class="hljs-keyword">compile</span> garna parney hunxa ani matra tapai ko <span class="hljs-built_in">code</span> le <span class="hljs-keyword">output</span> dinxa.`

![image](https:<span class="hljs-comment">//user-images.githubusercontent.com/67673221/209978704-452ab55e-f44c-4e0e-a82f-68b4657956ba.png)</span>


Yedi tapai le lekhnu vako c <span class="hljs-built_in">code</span> le `Hello World!`  <span class="hljs-keyword">output</span> diyo vane Congratulation! Tapai le pailo C program lekhnu vayo.

<span class="hljs-meta"># Syntax</span>
Tapai le  <span class="hljs-built_in">code</span> lekhera <span class="hljs-keyword">run</span> garnu ta vayo aaba teslai bujna lai tyo <span class="hljs-built_in">code</span> lai part part ma <span class="hljs-keyword">break</span> garxaum, tapai le aajha ramrari bujnu hunxa:
Yeso aaba tapai le vharkhar lekhnu vako <span class="hljs-built_in">code</span> ko <span class="hljs-number">1</span>st <span class="hljs-keyword">line</span> ma hernus ta tapaile:

`<span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> &lt;stdio.h&gt;` lekhnu vako xa yo line le stdio.h vanne file lai tapai ko program ma <span class="hljs-meta-keyword">include</span> garauxa stdio vaneko chai `standard input/output` arthat yo file ko help bata tapai le aafno lekhiyeko code ma input ra output lina ra dina paunu hunxa.</span>

<span class="hljs-keyword">For</span> Example: 

Mathi `<span class="hljs-keyword">Line</span> <span class="hljs-number">5</span>` ma `printf()` lekhnu vako xa yo function le <span class="hljs-keyword">Output</span> diney kaam garxa, jastai tapai le mathi printf ko bracket vhitra Hello World! Lekhnu vako thiyo.

Teslai `printf()` vanne function le <span class="hljs-keyword">print</span> garera <span class="hljs-keyword">output</span> ma Hello World! dekhaidiyo.

Ajhai bujnu vayena? Chinta nalinuhos yedi tapaile `<span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> &lt;stdio.h&gt;` le kasari  kaam garxa vanera bujnu vayeko xaina vane, yeslai kehi euta chiz (something) ko rupp ma linu hos laagbaag tapaile lekhnu vako hareko program haru ma use hunxa.</span>


- Aaba <span class="hljs-keyword">line</span> <span class="hljs-number">3</span> ma hernuhos arko kura jun jaile tapaile leknu vako c program ma dekha parxa `main()`. Yeslai chai main function vaninxa tapaile `{}` curly bracket vhitra lekhnu vayeko <span class="hljs-built_in">code</span> lai compiler le execute garxa <span class="hljs-keyword">or</span> execute hunxa.
- <span class="hljs-keyword">Line</span> <span class="hljs-number">5</span> ma `printf()` function xa jun chai <span class="hljs-keyword">screen</span> ma <span class="hljs-keyword">output</span> dina lai <span class="hljs-keyword">use</span> hunxa, jastai mathi ko <span class="hljs-built_in">code</span> ma `Hello World!`.

- Important kura C <span class="hljs-built_in">code</span> ko statement chai jaile semicolon `;` le <span class="hljs-keyword">end</span> garxa.
- <span class="hljs-keyword">Line</span> <span class="hljs-number">7</span> ma lekhiyeko `<span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;` le chai main function lai <span class="hljs-built_in">close</span> <span class="hljs-keyword">or</span> <span class="hljs-keyword">end</span> garxa.
- <span class="hljs-keyword">Line</span> <span class="hljs-number">8</span> ma chai curly bracket <span class="hljs-built_in">close</span> gareko xaum hamle ekchoti bracket <span class="hljs-keyword">open</span> garepaxi teslai compulsory <span class="hljs-built_in">close</span> garnai parxa.

<span class="hljs-meta"># C Output </span>
Aaba hamle kei kura <span class="hljs-keyword">or</span> value <span class="hljs-keyword">print</span> garna paryo vane hamle `printf()` function <span class="hljs-keyword">use</span> garxaum:

```C
<span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> &lt;stdio.h&gt;</span>

int main(){
    printf(<span class="hljs-string">"Orphic"</span>);
    <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;
}
</code></pre><p>Output:<code>Orphic</code></p>
<p>Hamle jati pani <code>printf()</code> use garna pauxa.</p>
<pre><code class="lang-C"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;stdio.h&gt;</span></span>

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span></span>{
    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"Orphic"</span>);
    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"Rethink, Recode!"</span>);
    <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;
}
</code></pre>
<p>Output: <code>OrphicRethink, Recode!</code></p>
<p>Tapaile Note garna parne kura chai k ho vaney printf le print matra garxa naya line ma print garaudaina.</p>
<p>Naya printf() ko content lai naya line ma print garuna last ma <code>\n</code> use garna parxa.</p>
<pre><code class="lang-C"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;stdio.h&gt;</span></span>

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span></span>{
    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"Orphic\n"</span>);
    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"Rethink, Recode!"</span>);
    <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;
}
</code></pre>
<p>Output: </p>
<pre><code>Orphic
Rethink, Recode!
</code></pre><p>Hamle <code>\n</code> character use garesi tala ko printf ko content naya line ma print vayo.</p>
<h1 id="comments-in-c">Comments in C</h1>
<p>Simply, Tapaile tapai ko sathi ko photo ma comment garnu hunxa ni testai ho yesma ni comments use garera certain block of code lai explain garna or remainder ko lagi use garinxa.</p>
<ul>
<li>Singled-Lined Comments (//)</li>
<li><p>Multi-Lined Comments (/<em>   </em>/)</p>
<p>Aaba hami yo mathi comment character lai hamro code ma use garxaum.</p>
<pre><code><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;stdio.h&gt;</span></span>

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span></span>{
<span class="hljs-comment">// this is single line comment</span>
<span class="hljs-comment">/* this is
multi-line comments
*/</span>
  <span class="hljs-built_in">printf</span>(<span class="hljs-string">"Hello World!"</span>);
  <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;
}
</code></pre><p>Output:<code>Hello World!</code></p>
</li>
</ul>
<p>Hamle Comments ma lekheko kura haru lai compiler le purai ignore garxa.</p>
<h1 id="c-variables">C Variables</h1>
<p>Variables vaneko chai euta container ho euta vada ho jasma chai kei data haru store hunxa.
Sochnus tapai snga euta glass xa ni tyo glass ma pani:
<code>glass = water</code> vanesi Variable vaneko chai glass ho jasle chai water vanne value carry garirako xa tyo value tapaile piuna lai use garna milxa.</p>
<p>Tesai gari hamle programming ma Variable kunai pani data store garney ani paxi hamle kunai function or mathmatical logic ma use garna milxa.</p>
<p>C ma chai diffrent types on variable hunxa (datatype declare gareko anusar le tapai ko variable le value carry garxa)</p>
<ul>
<li>int: numeric value or whole number store garxa jastai: <code>123</code>, <code>-123</code>.</li>
<li>float: floating point or decimal value store garxa, <code>15.65</code> or <code>-35.65</code>.</li>
<li>char: yesle chai single character haru store garxa jastai <code>a</code> or <code>A</code>.</li>
</ul>
<h2 id="declaring-variables">Declaring Variables</h2>
<p>Hamle variables declare garna vanda paila types specify garna parxa.</p>
<p><code>type variableName = value;</code></p>
<p>where <code>type</code> ma datatype rakhne (jastai int jasle number carry garxa) ani <code>variableName</code> ma (jastai x or number int value store garna lai) <code>=</code> vaneko chai tapai ko variable ko value assign garna lai.</p>
<p>Aaba chai hami variable  banauxau jasko  data type <code>int</code> hunxa  ani naam <code>number</code> hunxa tespaxi tesko value <code>10</code> vanera assign garxaum haita:</p>
<p><code>int number = 10;</code></p>
<p>hamle value binaa declare garna ni milxa jastai:</p>
<p><code>int number;</code></p>
<p>yo garda chai paxi hamle user bata value lina parxa ani number vanne variable ma store garna parxa yo kura hami arko part ma sikxau.</p>
<p>Aaba hamle tyo number vako 10 value lai print garna parxa tara tapai haru le euta kura bujna parxa:</p>
<p>Aru programming language haru ma variable ko value print garna lai direct print() vanne function ko bracket vhitra varibale ko naam haldina:</p>
<pre><code class="lang-python"><span class="hljs-built_in">num</span> = <span class="hljs-number">10</span>

<span class="hljs-built_in">print</span>(<span class="hljs-built_in">num</span>)
</code></pre>
<p>Tara c language ma chai yesari kei pani print hudaina. Print garauna lai hamle fomat specifiers use garna parney hunxa.</p>
<p>So, aaba hami paila format specifiers ko barema halka herxau.</p>
<h1 id="format-specifiers">Format specifiers</h1>
<p>Format Specifiers chai hamle printf() function use garxaum kina garxaum vhanda, compiler lai variable vhitra store gariyeko data type ko barema bujauna lai.</p>
<p>Format Specifiers chai <code>%</code> yo sign le start hunxa.</p>
<p>For example, aagi hami le lekheko program <code>int num = 10</code> ma variable le <code>int</code> matlab integer value carry gareko xa. Aaba tyo integer lai print garna lai hamle <code>%d</code> or <code>%i</code> use garnu parney hunxa.</p>
<pre><code class="lang-C"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;stdio.h&gt;</span></span>

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span></span>{

    <span class="hljs-keyword">int</span> num = <span class="hljs-number">10</span>;

    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"%d"</span>, num);

    <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;

}
</code></pre>
<p>Output: <code>10</code></p>
<pre><code>Note:
- <span class="hljs-keyword">int</span> ko <span class="hljs-keyword">format</span> specifiers %d ra %i ho.
- flaot ko <span class="hljs-keyword">format</span> specifiers %f ho.
- char ko fomat specifiers chai %c ho.
</code></pre><p>Tala ko program ma hami sabai format specifiers use garera value print garxaum haita.</p>
<pre><code class="lang-C"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;stdio.h&gt;</span></span>

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span></span>{

    <span class="hljs-keyword">int</span> num = <span class="hljs-number">10</span>;
    <span class="hljs-keyword">float</span> num_1 = <span class="hljs-number">23.55</span>;
    <span class="hljs-keyword">char</span> name = <span class="hljs-string">'S'</span>;

    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"%d"</span>, num);
    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"%f"</span>, num_1);
    <span class="hljs-built_in">printf</span>(<span class="hljs-string">"%c"</span>, name);

    <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;

}
</code></pre>
<p>Output:</p>
<pre><code><span class="hljs-number">10</span>
<span class="hljs-number">23.55</span>
S
</code></pre><p>Text ra variable ko value combine garna printf function vhitra comma le seprate garna parxa.
jastai:</p>
<pre><code class="lang-C"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;stdio.h&gt;</span></span>

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span> </span>{
  <span class="hljs-keyword">int</span> num = <span class="hljs-number">15</span>;
  <span class="hljs-built_in">printf</span>(<span class="hljs-string">"Number: %d"</span>, num);
  <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;
}
</code></pre>
<p>Output:<code>Number: 15</code></p>
<h2 id="general-rules-for-naming-variables">General rules for naming Variables</h2>
<ul>
<li>Tapai le declare garnu vako variable le letter, digits ani underscore matra hunapauxa.</li>
<li>variable name jaile underscore or underscore le start garna parney hunxa.</li>
<li>variable name haru case sensitive hunxa <code>num</code> ra <code>Num</code> xuttai xuttai variable ko roop ma chinxa c language le.</li>
<li>aani variable name ma chai kaile whitespaces or special character jastai: !, #, %, etc use garna paidaina.</li>
<li>C ma reserved vayeko naam jastai:<code>int, char, etc</code> haru pani use garna paidaina.</li>
</ul>
<h1 id="data-types">Data types</h1>
<p>Aagi vaneko jastai C language ma variable ma data type specify garna parxa ani sang sangai format specifiers ni print garne bela.</p>
<h2 id="basic-datatypes">Basic Datatypes</h2>
<p>Data type le chai variable ma store vayeko information ko size ra type lai specify garxa.</p>
<p>Hami yo tutorial ma chai basic datatype haru ma focus garxaum:</p>
<pre><code>- <span class="hljs-built_in">int</span> : yesle whole <span class="hljs-keyword">number</span> haru store garxa ra yesko <span class="hljs-built_in">size</span> vaneko <span class="hljs-number">2</span> or <span class="hljs-number">4</span> bytes ko hunxa.
- <span class="hljs-built_in">float</span> : <span class="hljs-number">6</span> <span class="hljs-keyword">decimal</span> <span class="hljs-built_in">digits</span> <span class="hljs-keyword">value</span> store garxa ani yesko <span class="hljs-built_in">size</span> vaneko <span class="hljs-number">4</span> bytes ko hunxa.
- <span class="hljs-keyword">double</span>: <span class="hljs-number">15</span> <span class="hljs-keyword">decimal</span> <span class="hljs-built_in">digits</span> <span class="hljs-keyword">value</span> store garxa ani yesko <span class="hljs-built_in">size</span> chai <span class="hljs-number">8</span> bytes ko hunxa.
- <span class="hljs-built_in">char</span> : yesle chai single <span class="hljs-keyword">character</span>, letter, <span class="hljs-keyword">number</span>, or ascii values store garxa ra yesko <span class="hljs-built_in">size</span> vaneko chai <span class="hljs-number">1</span> byte  ko hunxa.
</code></pre><h2 id="format-specifiers">Format Specifiers</h2>
<ul>
<li>int: <code>%d</code> or <code>%i</code>.</li>
<li>float: <code>%f</code></li>
<li>double: <code>%lf</code></li>
<li>char: <code>%c</code></li>
<li>string: <code>%s</code></li>
</ul>
