<p><strong>C</strong>&nbsp;is a&nbsp;<a title="General-purpose language" href="https://en.wikipedia.org/wiki/General-purpose_language">general-purpose</a>,&nbsp;<a title="Procedural programming" href="https://en.wikipedia.org/wiki/Procedural_programming">procedural</a>&nbsp;computer&nbsp;<a title="Programming language" href="https://en.wikipedia.org/wiki/Programming_language">programming language</a>&nbsp;supporting&nbsp;<a title="Structured programming" href="https://en.wikipedia.org/wiki/Structured_programming">structured programming</a>,&nbsp;<a class="mw-redirect" title="" href="https://en.wikipedia.org/wiki/Lexical_variable_scope">lexical variable scope</a>, and&nbsp;<a title="Recursion (computer science)" href="https://en.wikipedia.org/wiki/Recursion_(computer_science)">recursion</a>, while a&nbsp;<a class="mw-redirect" title="Static type system" href="https://en.wikipedia.org/wiki/Static_type_system">static type system</a>&nbsp;prevents unintended operations. By design, C provides constructs that map efficiently to typical&nbsp;<a title="Machine code" href="https://en.wikipedia.org/wiki/Machine_code">machine instructions</a>&nbsp;and has found lasting use in applications previously coded in&nbsp;<a title="Assembly language" href="https://en.wikipedia.org/wiki/Assembly_language">assembly language</a>. Such applications include&nbsp;<a title="Operating system" href="https://en.wikipedia.org/wiki/Operating_system">operating systems</a>&nbsp;and various&nbsp;<a title="Application software" href="https://en.wikipedia.org/wiki/Application_software">application software</a>&nbsp;for computers, from&nbsp;<a title="Supercomputer" href="https://en.wikipedia.org/wiki/Supercomputer">supercomputers</a>&nbsp;to&nbsp;<a title="Embedded system" href="https://en.wikipedia.org/wiki/Embedded_system">embedded systems</a>.</p>
<p>C was originally developed at&nbsp;<a title="Bell Labs" href="https://en.wikipedia.org/wiki/Bell_Labs">Bell Labs</a>&nbsp;by&nbsp;<a title="Dennis Ritchie" href="https://en.wikipedia.org/wiki/Dennis_Ritchie">Dennis Ritchie</a>&nbsp;between 1972 and 1973 to make utilities running on&nbsp;<a title="Unix" href="https://en.wikipedia.org/wiki/Unix">Unix</a>. Later, it was applied to re-implementing the kernel of the Unix operating system.&nbsp;During the 1980s, C gradually gained popularity. It has become one of the&nbsp;<a title="Measuring programming language popularity" href="https://en.wikipedia.org/wiki/Measuring_programming_language_popularity">most widely used programming languages</a>,&nbsp;with C&nbsp;<a title="Compiler" href="https://en.wikipedia.org/wiki/Compiler">compilers</a>&nbsp;from various vendors available for the majority of existing&nbsp;<a title="Computer architecture" href="https://en.wikipedia.org/wiki/Computer_architecture">computer architectures</a>&nbsp;and operating systems. C has been standardized by the&nbsp;<a title="American National Standards Institute" href="https://en.wikipedia.org/wiki/American_National_Standards_Institute">ANSI</a>&nbsp;since 1989 (see&nbsp;<a title="ANSI C" href="https://en.wikipedia.org/wiki/ANSI_C">ANSI C</a>) and by the&nbsp;<a title="International Organization for Standardization" href="https://en.wikipedia.org/wiki/International_Organization_for_Standardization">International Organization for Standardization</a>.</p>
<p>C is an&nbsp;<a title="Imperative programming" href="https://en.wikipedia.org/wiki/Imperative_programming">imperative</a>&nbsp;<a title="Procedural programming" href="https://en.wikipedia.org/wiki/Procedural_programming">procedural</a>&nbsp;language. It was designed to be compiled using a relatively straightforward&nbsp;<a title="Compiler" href="https://en.wikipedia.org/wiki/Compiler">compiler</a>&nbsp;to provide&nbsp;<a title="Low-level programming language" href="https://en.wikipedia.org/wiki/Low-level_programming_language">low-level</a>&nbsp;access to&nbsp;<a title="Computer memory" href="https://en.wikipedia.org/wiki/Computer_memory">memory</a>&nbsp;and language constructs that map efficiently to&nbsp;<a title="Machine code" href="https://en.wikipedia.org/wiki/Machine_code">machine instructions</a>, all with minimal&nbsp;<a title="Runtime system" href="https://en.wikipedia.org/wiki/Runtime_system">runtime support</a>. Despite its low-level capabilities, the language was designed to encourage&nbsp;<a title="Cross-platform software" href="https://en.wikipedia.org/wiki/Cross-platform_software">cross-platform</a>&nbsp;programming. A&nbsp;<a title="Specification (technical standard)" href="https://en.wikipedia.org/wiki/Specification_(technical_standard)">standards</a>-compliant C program written with&nbsp;<a title="Porting" href="https://en.wikipedia.org/wiki/Porting">portability</a>&nbsp;in mind can be compiled for a wide variety of computer platforms and operating systems with few changes to its source code. The language is available on various platforms, from embedded&nbsp;<a title="Microcontroller" href="https://en.wikipedia.org/wiki/Microcontroller">microcontrollers</a>&nbsp;to&nbsp;<a title="Supercomputer" href="https://en.wikipedia.org/wiki/Supercomputer">supercomputers</a>.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>




<div class="toctitle" dir="ltr" lang="en">
<h2>Contents</h2>
<label class="toctogglelabel" for="toctogglecheckbox"></label></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="#Overview"><span class="toctext">Overview</span></a>
<ul>
<li class="toclevel-2 tocsection-2"><a href="#Relations_to_other_languages"><span class="toctext">Relations to other languages</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-3"><a href="#History"><span class="toctext">History</span></a>
<ul>
<li class="toclevel-2 tocsection-4"><a href="#Early_developments"><span class="toctext">Early developments</span></a></li>
<li class="toclevel-2 tocsection-5"><a href="#K&amp;R_C"><span class="toctext">K&amp;R C</span></a></li>
<li class="toclevel-2 tocsection-6"><a href="#ANSI_C_and_ISO_C"><span class="toctext">ANSI C and ISO C</span></a></li>
<li class="toclevel-2 tocsection-7"><a href="#C99"><span class="toctext">C99</span></a></li>
<li class="toclevel-2 tocsection-8"><a href="#C11"><span class="toctext">C11</span></a></li>
<li class="toclevel-2 tocsection-9"><a href="#C18"><span class="toctext">C18</span></a></li>
<li class="toclevel-2 tocsection-10"><a href="#Embedded_C"><span class="toctext">Embedded C</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-11"><a href="#Syntax"><span class="toctext">Syntax</span></a>
<ul>
<li class="toclevel-2 tocsection-12"><a href="#Character_set"><span class="toctext">Character set</span></a></li>
<li class="toclevel-2 tocsection-13"><a href="#Reserved_words"><span class="toctext">Reserved words</span></a></li>
<li class="toclevel-2 tocsection-14"><a href="#Operators"><span class="toctext">Operators</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-15"><a href="#%22Hello,_world%22_example"><span class="toctext">"Hello, world" example</span></a></li>
<li class="toclevel-1 tocsection-16"><a href="#Data_types"><span class="toctext">Data types</span></a>
<ul>
<li class="toclevel-2 tocsection-17"><a href="#Pointers"><span class="toctext">Pointers</span></a></li>
<li class="toclevel-2 tocsection-18"><a href="#Arrays"><span class="toctext">Arrays</span></a></li>
<li class="toclevel-2 tocsection-19"><a href="#Array%E2%80%93pointer_interchangeability"><span class="toctext">Array&ndash;pointer interchangeability</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-20"><a href="#Memory_management"><span class="toctext">Memory management</span></a></li>
<li class="toclevel-1 tocsection-21"><a href="#Libraries"><span class="toctext">Libraries</span></a>
<ul>
<li class="toclevel-2 tocsection-22"><a href="#File_handling_and_streams"><span class="toctext">File handling and streams</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-23"><a href="#Language_tools"><span class="toctext">Language tools</span></a></li>
<li class="toclevel-1 tocsection-24"><a href="#Uses"><span class="toctext">Uses</span></a></li>
<li class="toclevel-1 tocsection-25"><a href="#Related_languages"><span class="toctext">Related languages</span></a></li>
</ul>



<p>&nbsp;</p>
<p>&nbsp;</p>









<h2><span id="Overview" class="mw-headline">Overview</span></h2>
<div class="thumb tright">
<div class="thumbinner"><a class="image" href="den.jpg"><img class="thumbimage" style="display: block; margin-left: auto; margin-right: auto;" src="den.jpg" srcset="den.jpg 1.5x" alt="" width="220" height="143" data-file-width="310" data-file-height="201" /></a>
<div class="thumbcaption" style="text-align: center;">
<div class="magnify">&nbsp;</div>
<strong><a title="Dennis Ritchie" href="https://en.wikipedia.org/wiki/Dennis_Ritchie">Dennis Ritchie</a>&nbsp;(right), the inventor of the C programming language, with&nbsp;<a title="Ken Thompson" href="https://en.wikipedia.org/wiki/Ken_Thompson">Ken Thompson</a></strong></div>
<div class="thumbcaption">&nbsp;</div>
<div class="thumbcaption">&nbsp;</div>
</div>
</div>
<p>Like most procedural languages in the&nbsp;<a title="ALGOL" href="https://en.wikipedia.org/wiki/ALGOL">ALGOL</a>&nbsp;tradition, C has facilities for&nbsp;<a title="Structured programming" href="https://en.wikipedia.org/wiki/Structured_programming">structured programming</a>&nbsp;and allows&nbsp;<a class="mw-redirect" title="Lexical variable scope" href="https://en.wikipedia.org/wiki/Lexical_variable_scope">lexical variable scope</a>&nbsp;and recursion. Its static&nbsp;<a title="Type system" href="https://en.wikipedia.org/wiki/Type_system">type system</a>&nbsp;prevents unintended operations. In C, all&nbsp;<a class="mw-redirect" title="Executable code" href="https://en.wikipedia.org/wiki/Executable_code">executable code</a>&nbsp;is contained within&nbsp;<a title="Subroutine" href="https://en.wikipedia.org/wiki/Subroutine">subroutines</a>&nbsp;(also called "functions", though not strictly in the sense of&nbsp;<a title="Functional programming" href="https://en.wikipedia.org/wiki/Functional_programming">functional programming</a>).&nbsp;<a title="Parameter (computer programming)" href="https://en.wikipedia.org/wiki/Parameter_(computer_programming)">Function parameters</a>&nbsp;are always passed by value. Pass-by-reference is simulated in C by explicitly passing&nbsp;<a title="Pointer (computer programming)" href="https://en.wikipedia.org/wiki/Pointer_(computer_programming)">pointer</a>&nbsp;values. C program source text is&nbsp;<a title="Free-form language" href="https://en.wikipedia.org/wiki/Free-form_language">free-format</a>, using the&nbsp;<a title="Semicolon" href="https://en.wikipedia.org/wiki/Semicolon">semicolon</a>&nbsp;as a&nbsp;<a class="mw-redirect" title="Statement (programming)" href="https://en.wikipedia.org/wiki/Statement_(programming)">statement</a>&nbsp;terminator and&nbsp;<a class="mw-redirect" title="Curly braces" href="https://en.wikipedia.org/wiki/Curly_braces">curly braces</a>&nbsp;for grouping&nbsp;<a class="mw-redirect" title="Blocks of statements" href="https://en.wikipedia.org/wiki/Blocks_of_statements">blocks of statements</a>.</p>
<p>The C language also exhibits the following characteristics:</p>
<ul>
<li>The language has a small, fixed number of keywords, including a full set of&nbsp;<a title="Control flow" href="https://en.wikipedia.org/wiki/Control_flow">control flow</a>&nbsp;primitives:&nbsp;<code><a title="Conditional (computer programming)" href="https://en.wikipedia.org/wiki/Conditional_(computer_programming)">if/else</a></code>,&nbsp;<code><a title="For loop" href="https://en.wikipedia.org/wiki/For_loop">for</a></code>,&nbsp;<code><a title="Do while loop" href="https://en.wikipedia.org/wiki/Do_while_loop">do/while</a></code>,&nbsp;<code><a title="While loop" href="https://en.wikipedia.org/wiki/While_loop">while</a></code>, and&nbsp;<code><a title="Switch statement" href="https://en.wikipedia.org/wiki/Switch_statement">switch</a></code>. User-defined names are not distinguished from keywords by any kind of&nbsp;<a title="Sigil (computer programming)" href="https://en.wikipedia.org/wiki/Sigil_(computer_programming)">sigil</a>.</li>
<li>It has a large number of arithmetic, bitwise, and logic operators:&nbsp;<code>+</code>,&nbsp;<code>+=</code>,&nbsp;<code>++</code>,&nbsp;<code>&amp;</code>,&nbsp;<code>||</code>, etc.</li>
<li>More than one&nbsp;<a title="Assignment (computer science)" href="https://en.wikipedia.org/wiki/Assignment_(computer_science)">assignment</a>&nbsp;may be performed in a single statement.</li>
<li>Functions:
<ul>
<li>Function return values can be ignored, when not needed.</li>
<li>Function and data pointers permit&nbsp;<em>ad hoc</em>&nbsp;<a class="mw-redirect" title="Run-time polymorphism" href="https://en.wikipedia.org/wiki/Run-time_polymorphism">run-time polymorphism</a>.</li>
<li>Functions may not be defined within the lexical scope of other functions.</li>
</ul>
</li>
<li>Data typing is&nbsp;<a class="mw-redirect" title="Static typing" href="https://en.wikipedia.org/wiki/Static_typing">static</a>, but&nbsp;<a title="Strong and weak typing" href="https://en.wikipedia.org/wiki/Strong_and_weak_typing">weakly enforced</a>; all data has a type, but&nbsp;<a class="mw-redirect" title="Implicit conversion" href="https://en.wikipedia.org/wiki/Implicit_conversion">implicit conversions</a>&nbsp;are possible.</li>
<li><a title="Declaration (computer programming)" href="https://en.wikipedia.org/wiki/Declaration_(computer_programming)">Declaration</a>&nbsp;<a title="C syntax" href="https://en.wikipedia.org/wiki/C_syntax">syntax</a>&nbsp;mimics usage context. C has no "define" keyword; instead, a statement beginning with the name of a type is taken as a declaration. There is no "function" keyword; instead, a function is indicated by the presence of a parenthesized argument list.</li>
<li>User-defined (<a title="Typedef" href="https://en.wikipedia.org/wiki/Typedef">typedef</a>) and compound types are possible.
<ul>
<li>Heterogeneous aggregate data types (<code><a title="Struct (C programming language)" href="https://en.wikipedia.org/wiki/Struct_(C_programming_language)">struct</a></code>) allow related data elements to be accessed and assigned as a unit.</li>
<li><a title="Union type" href="https://en.wikipedia.org/wiki/Union_type">Union</a>&nbsp;is a structure with overlapping members; only the last member stored is valid.</li>
<li><a title="Array data type" href="https://en.wikipedia.org/wiki/Array_data_type">Array</a>&nbsp;indexing is a secondary notation, defined in terms of pointer arithmetic. Unlike structs, arrays are not first-class objects: they cannot be assigned or compared using single built-in operators. There is no "array" keyword in use or definition; instead, square brackets indicate arrays syntactically, for example&nbsp;<code>month[11]</code>.</li>
<li><a title="Enumerated type" href="https://en.wikipedia.org/wiki/Enumerated_type">Enumerated types</a>&nbsp;are possible with the&nbsp;<code>enum</code>&nbsp;keyword. They are freely interconvertible with integers.</li>
<li><a title="String (computer science)" href="https://en.wikipedia.org/wiki/String_(computer_science)">Strings</a>&nbsp;are not a distinct data type, but are conventionally&nbsp;<a title="C string handling" href="https://en.wikipedia.org/wiki/C_string_handling">implemented</a>&nbsp;as&nbsp;<a title="Null-terminated string" href="https://en.wikipedia.org/wiki/Null-terminated_string">null-terminated</a>&nbsp;character arrays.</li>
</ul>
</li>
<li>Low-level access to&nbsp;<a title="Computer memory" href="https://en.wikipedia.org/wiki/Computer_memory">computer memory</a>&nbsp;is possible by converting machine addresses to typed&nbsp;<a title="Pointer (computer programming)" href="https://en.wikipedia.org/wiki/Pointer_(computer_programming)">pointers</a>.</li>
<li><a class="mw-redirect" title="Procedure (computer science)" href="https://en.wikipedia.org/wiki/Procedure_(computer_science)">Procedures</a>&nbsp;(subroutines not returning values) are a special case of function, with an untyped return type&nbsp;<code>void</code>.</li>
<li>A&nbsp;<a title="C preprocessor" href="https://en.wikipedia.org/wiki/C_preprocessor">preprocessor</a>&nbsp;performs&nbsp;<a title="Macro (computer science)" href="https://en.wikipedia.org/wiki/Macro_(computer_science)">macro</a>&nbsp;definition,&nbsp;<a title="Source code" href="https://en.wikipedia.org/wiki/Source_code">source code</a>&nbsp;file inclusion, and&nbsp;<a title="Conditional compilation" href="https://en.wikipedia.org/wiki/Conditional_compilation">conditional compilation</a>.</li>
<li>There is a basic form of&nbsp;<a title="Modular programming" href="https://en.wikipedia.org/wiki/Modular_programming">modularity</a>: files can be compiled separately and&nbsp;<a title="Linker (computing)" href="https://en.wikipedia.org/wiki/Linker_(computing)">linked</a>&nbsp;together, with control over which functions and data objects are visible to other files via&nbsp;<a title="Static (keyword)" href="https://en.wikipedia.org/wiki/Static_(keyword)"><code>static</code></a>&nbsp;and&nbsp;<code>extern</code>&nbsp;attributes.</li>
<li>Complex functionality such as&nbsp;<a title="Input/output" href="https://en.wikipedia.org/wiki/Input/output">I/O</a>,&nbsp;<a title="String (computer science)" href="https://en.wikipedia.org/wiki/String_(computer_science)">string</a>&nbsp;manipulation, and mathematical functions are consistently delegated to&nbsp;<a title="Library (computing)" href="https://en.wikipedia.org/wiki/Library_(computing)">library routines</a>.</li>
</ul>
<p>While C does not include certain features found in other languages (such as&nbsp;<a title="Object-oriented programming" href="https://en.wikipedia.org/wiki/Object-oriented_programming">object orientation</a>&nbsp;and&nbsp;<a title="Garbage collection (computer science)" href="https://en.wikipedia.org/wiki/Garbage_collection_(computer_science)">garbage collection</a>), these can be implemented or emulated, often through the use of external libraries (e.g., the&nbsp;<a title="GObject" href="https://en.wikipedia.org/wiki/GObject">GLib Object System</a>&nbsp;or the&nbsp;<a title="Boehm garbage collector" href="https://en.wikipedia.org/wiki/Boehm_garbage_collector">Boehm garbage collector</a>).</p>


<h3><span id="Relations_to_other_languages" class="mw-headline">Relations to other languages</span></h3>
<p>Many later languages have borrowed directly or indirectly from C, including&nbsp;<a title="C++" href="https://en.wikipedia.org/wiki/C%2B%2B">C++</a>,&nbsp;<a title="C Sharp (programming language)" href="https://en.wikipedia.org/wiki/C_Sharp_(programming_language)">C#</a>, Unix's&nbsp;<a title="C shell" href="https://en.wikipedia.org/wiki/C_shell">C shell</a>,&nbsp;<a title="D (programming language)" href="https://en.wikipedia.org/wiki/D_(programming_language)">D</a>,&nbsp;<a title="Go (programming language)" href="https://en.wikipedia.org/wiki/Go_(programming_language)">Go</a>,&nbsp;<a title="Java (programming language)" href="https://en.wikipedia.org/wiki/Java_(programming_language)">Java</a>,&nbsp;<a title="JavaScript" href="https://en.wikipedia.org/wiki/JavaScript">JavaScript</a>&nbsp;(including&nbsp;<a title="JavaScript" href="https://en.wikipedia.org/wiki/JavaScript#transpilers">transpilers</a>),&nbsp;<a title="Limbo (programming language)" href="https://en.wikipedia.org/wiki/Limbo_(programming_language)">Limbo</a>,&nbsp;<a title="LPC (programming language)" href="https://en.wikipedia.org/wiki/LPC_(programming_language)">LPC</a>,&nbsp;<a title="Objective-C" href="https://en.wikipedia.org/wiki/Objective-C">Objective-C</a>,&nbsp;<a title="Perl" href="https://en.wikipedia.org/wiki/Perl">Perl</a>,&nbsp;<a title="PHP" href="https://en.wikipedia.org/wiki/PHP">PHP</a>,&nbsp;<a title="Python (programming language)" href="https://en.wikipedia.org/wiki/Python_(programming_language)">Python</a>,&nbsp;<a title="Rust (programming language)" href="https://en.wikipedia.org/wiki/Rust_(programming_language)">Rust</a>,&nbsp;<a title="Swift (programming language)" href="https://en.wikipedia.org/wiki/Swift_(programming_language)">Swift</a>,&nbsp;<a title="Verilog" href="https://en.wikipedia.org/wiki/Verilog">Verilog</a>&nbsp;and&nbsp;<a title="SystemVerilog" href="https://en.wikipedia.org/wiki/SystemVerilog">SystemVerilog</a>&nbsp;(hardware description languages).&nbsp;These languages have drawn many of their&nbsp;<a class="mw-redirect" title="Control structures" href="https://en.wikipedia.org/wiki/Control_structures">control structures</a>&nbsp;and other basic features from C. Most of them (Python being a dramatic exception) also express highly similar&nbsp;<a title="Syntax (programming languages)" href="https://en.wikipedia.org/wiki/Syntax_(programming_languages)">syntax</a>&nbsp;to C, and they tend to combine the recognizable expression and statement&nbsp;<a title="C syntax" href="https://en.wikipedia.org/wiki/C_syntax">syntax of C</a>&nbsp;with underlying type systems, data models, and semantics that can be radically different.</p>



<h2><span id="History" class="mw-headline">History</span></h2>
<h3><span id="Early_developments" class="mw-headline">Early developments</span></h3>
<table class="wikitable floatright" style="width: 175px;"><caption>Timeline of language development</caption>
<tbody>
<tr>
<th style="width: 61px;">Year</th>
<th style="width: 100px;">C Standard</th>
</tr>
<tr>
<td style="width: 61px;">1972</td>
<td style="width: 100px;">Birth</td>
</tr>
<tr>
<td style="width: 61px;">1978</td>
<td style="width: 100px;">K&amp;R C</td>
</tr>
<tr>
<td style="width: 61px;">1989/1990</td>
<td style="width: 100px;">ANSI C and ISO C</td>
</tr>
<tr>
<td style="width: 61px;">1999</td>
<td style="width: 100px;">C99</td>
</tr>
<tr>
<td style="width: 61px;">2011</td>
<td style="width: 100px;">C11</td>
</tr>
<tr>
<td style="width: 61px;">2017/2018</td>
<td style="width: 100px;">C18</td>
</tr>
</tbody>
</table>
<p>The origin of C is closely tied to the development of the&nbsp;<a title="Unix" href="https://en.wikipedia.org/wiki/Unix">Unix</a>&nbsp;operating system, originally implemented in&nbsp;<a title="Assembly language" href="https://en.wikipedia.org/wiki/Assembly_language">assembly language</a>&nbsp;on a&nbsp;<a title="PDP-7" href="https://en.wikipedia.org/wiki/PDP-7">PDP-7</a>&nbsp;by Dennis Ritchie and Ken Thompson, incorporating several ideas from colleagues. Eventually, they decided to port the operating system to a&nbsp;<a title="PDP-11" href="https://en.wikipedia.org/wiki/PDP-11">PDP-11</a>. The original PDP-11 version of Unix was also developed in assembly language.</p>
<p>Thompson desired a programming language to make utilities for the new platform. At first, he tried to make a&nbsp;<a title="Fortran" href="https://en.wikipedia.org/wiki/Fortran">Fortran</a>&nbsp;compiler, but soon gave up the idea. Instead, he created a cut-down version of the recently developed&nbsp;<a title="BCPL" href="https://en.wikipedia.org/wiki/BCPL">BCPL</a>&nbsp;<a class="mw-redirect" title="Systems programming language" href="https://en.wikipedia.org/wiki/Systems_programming_language">systems programming language</a>. The official description of BCPL was not available at the time,&nbsp;and Thompson modified the syntax to be less wordy, producing the similar but somewhat simpler&nbsp;<a title="B (programming language)" href="https://en.wikipedia.org/wiki/B_(programming_language)">B</a>.&nbsp;However, few utilities were ultimately written in B because it was too slow, and B could not take advantage of PDP-11 features such as&nbsp;<a title="Byte" href="https://en.wikipedia.org/wiki/Byte">byte</a>&nbsp;addressability.</p>
<p>In 1972, Ritchie started to improve B, which resulted in creating a new language C.&nbsp;The C compiler and some utilities made with it were included in&nbsp;<a class="mw-redirect" title="Version 2 Unix" href="https://en.wikipedia.org/wiki/Version_2_Unix">Version 2 Unix</a>.</p>
<p>At&nbsp;<a class="mw-redirect" title="Version 4 Unix" href="https://en.wikipedia.org/wiki/Version_4_Unix">Version 4 Unix</a>, released in November 1973, the&nbsp;<a title="Unix" href="https://en.wikipedia.org/wiki/Unix">Unix</a>&nbsp;<a title="Kernel (operating system)" href="https://en.wikipedia.org/wiki/Kernel_(operating_system)">kernel</a>&nbsp;was extensively re-implemented in C.&nbsp;By this time, the C language had acquired some powerful features such as&nbsp;<code>struct</code>&nbsp;types.</p>
<p>Unix was one of the first operating system kernels implemented in a language other than&nbsp;<a title="Assembly language" href="https://en.wikipedia.org/wiki/Assembly_language">assembly</a>. Earlier instances include the&nbsp;<a title="Multics" href="https://en.wikipedia.org/wiki/Multics">Multics</a>&nbsp;system (which was written in&nbsp;<a title="PL/I" href="https://en.wikipedia.org/wiki/PL/I">PL/I</a>) and&nbsp;<a title="Burroughs MCP" href="https://en.wikipedia.org/wiki/Burroughs_MCP">Master Control Program</a>&nbsp;(MCP) for the&nbsp;<a title="Burroughs large systems" href="https://en.wikipedia.org/wiki/Burroughs_large_systems">Burroughs B5000</a>&nbsp;(which was written in&nbsp;<a title="ALGOL" href="https://en.wikipedia.org/wiki/ALGOL">ALGOL</a>) in 1961. In around 1977, Ritchie and&nbsp;<a title="Stephen C. Johnson" href="https://en.wikipedia.org/wiki/Stephen_C._Johnson">Stephen C. Johnson</a>&nbsp;made further changes to the language to facilitate portability of the Unix operating system. Johnson's&nbsp;<a title="Portable C Compiler" href="https://en.wikipedia.org/wiki/Portable_C_Compiler">Portable C Compiler</a>&nbsp;served as the basis for several implementations of C on new platforms.</p>












<ul>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(1).pdf" style="text-decoration:none;">C How to Program </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(2).pdf" style="text-decoration:none;">The C puzzle book</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(3).pdf" style="text-decoration:none;">Beginning C</a></b></li>
                               
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(4).pdf" style="text-decoration:none;">C For Dummies</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(5).pdf" style="text-decoration:none;">C, The Complete Reference </a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(6).pdf" style="text-decoration:none;">C Traps and Pitfalls</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(8).pdf" style="text-decoration:none;">Compiler Design in C</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(9).pdf" style="text-decoration:none;">The C Programming Language</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(10).pdf" style="text-decoration:none;">C: A Reference Manual</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(11).pdf" style="text-decoration:none;">Let Us C</a></b></li>  
        
<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(13).pdf" style="text-decoration:none;">Test Your C Skills </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(14).pdf" style="text-decoration:none;">Understanding and Using C Pointers</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(15).pdf" style="text-decoration:none;">Numerical Recipes in C: The Art of Scientific Computing</a></b></li>  
  <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(16).pdf" style="text-decoration:none;">C Programs with Solutions</a></b></li>  
 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(17).pdf" style="text-decoration:none;">The Unix Programming Environment</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(18).pdf" style="text-decoration:none;">Programming In Ansi C</a></b></li>

 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(7).pdf" style="text-decoration:none;">The Standard C Library</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(12).pdf" style="text-decoration:none;">C: Pocket Reference</a></b></li>

<li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(19).pdf" style="text-decoration:none;">Beginning Programming with C For Dummies</a></b></li>

 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(20).pdf" style="text-decoration:none;">The Development of the C Language</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(21).pdf" style="text-decoration:none;">Programming embedded systems in C and C++</a></b></li>

   <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(22).pdf" style="text-decoration:none;">Build Your Own Lisp: Learn C and build your own programming language in under 1000 lines of code!</a></b></li>

 <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(23).pdf" style="text-decoration:none;">A Book on C: Programming in C</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/C-Programming-Books/blob/master/cpl(24).pdf" style="text-decoration:none;">C For Dummies</a></b></li>


</ul>
                                
