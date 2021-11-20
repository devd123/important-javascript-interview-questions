<ol dir="auto">
  <li>
<h3 dir="auto"><a id="user-content-what-are-the-possible-ways-to-create-objects-in-javascript" class="anchor" aria-hidden="true" href="#what-are-the-possible-ways-to-create-objects-in-javascript"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are the possible ways to create objects in JavaScript</h3>
<p dir="auto">There are many ways to create objects in javascript as below</p>
<ol dir="auto">
<li>
<p dir="auto"><strong>Object constructor:</strong></p>
<p dir="auto">The simplest way to create an empty object is using the Object constructor. Currently this approach is not recommended.</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">var</span> <span class="pl-s1">object</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Object</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="var object = new Object();
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong>Object's create method:</strong></p>
<p dir="auto">The create method of Object creates a new object by passing the prototype object as a parameter</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">var</span> <span class="pl-s1">object</span> <span class="pl-c1">=</span> <span class="pl-v">Object</span><span class="pl-kos">.</span><span class="pl-en">create</span><span class="pl-kos">(</span><span class="pl-c1">null</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="var object = Object.create(null);
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong>Object literal syntax:</strong></p>
<p dir="auto">The object literal syntax is equivalent to create method when it passes null as parameter</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">var</span> <span class="pl-s1">object</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span><span class="pl-kos">}</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="var object = {};
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong>Function constructor:</strong></p>
<p dir="auto">Create any function and apply the new operator to create object instances,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">function</span> <span class="pl-v">Person</span><span class="pl-kos">(</span><span class="pl-s1">name</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
   <span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">name</span><span class="pl-c1">=</span><span class="pl-s1">name</span><span class="pl-kos">;</span>
   <span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">age</span><span class="pl-c1">=</span><span class="pl-c1">21</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>
<span class="pl-k">var</span> <span class="pl-s1">object</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Person</span><span class="pl-kos">(</span><span class="pl-s">"Sudheer"</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="function Person(name){
   this.name=name;
   this.age=21;
}
var object = new Person(&quot;Sudheer&quot;);
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong>Function constructor with prototype:</strong></p>
<p dir="auto">This is similar to function constructor but it uses prototype for their properties and methods,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">function</span> <span class="pl-v">Person</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">{</span><span class="pl-kos">}</span>
<span class="pl-v">Person</span><span class="pl-kos">.</span><span class="pl-c1">prototype</span><span class="pl-kos">.</span><span class="pl-c1">name</span> <span class="pl-c1">=</span> <span class="pl-s">"Sudheer"</span><span class="pl-kos">;</span>
<span class="pl-k">var</span> <span class="pl-s1">object</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Person</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="function Person(){}
Person.prototype.name = &quot;Sudheer&quot;;
var object = new Person();
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">This is equivalent to an instance created with an object create method with a function prototype and then call that function with an instance and parameters as arguments.</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">function</span> <span class="pl-s1">func</span> <span class="pl-kos">{</span><span class="pl-kos">}</span><span class="pl-kos">;</span>

<span class="pl-k">new</span> <span class="pl-s1">func</span><span class="pl-kos">(</span><span class="pl-s1">x</span><span class="pl-kos">,</span> <span class="pl-s1">y</span><span class="pl-kos">,</span> <span class="pl-s1">z</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="function func {};

new func(x, y, z);
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong>(OR)</strong></p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-c">// Create a new instance using function prototype.</span>
<span class="pl-k">var</span> <span class="pl-s1">newInstance</span> <span class="pl-c1">=</span> <span class="pl-v">Object</span><span class="pl-kos">.</span><span class="pl-en">create</span><span class="pl-kos">(</span><span class="pl-s1">func</span><span class="pl-kos">.</span><span class="pl-c1">prototype</span><span class="pl-kos">)</span>

<span class="pl-c">// Call the function</span>
<span class="pl-k">var</span> <span class="pl-s1">result</span> <span class="pl-c1">=</span> <span class="pl-s1">func</span><span class="pl-kos">.</span><span class="pl-en">call</span><span class="pl-kos">(</span><span class="pl-s1">newInstance</span><span class="pl-kos">,</span> <span class="pl-s1">x</span><span class="pl-kos">,</span> <span class="pl-s1">y</span><span class="pl-kos">,</span> <span class="pl-s1">z</span><span class="pl-kos">)</span><span class="pl-kos">,</span>

<span class="pl-c">// If the result is a non-null object then use it otherwise just use the new instance.</span>
<span class="pl-s1">console</span><span class="pl-kos">.</span><span class="pl-s1">log</span><span class="pl-kos">(</span><span class="pl-s1">result</span> <span class="pl-c1">&amp;&amp;</span> <span class="pl-k">typeof</span> <span class="pl-s1">result</span> <span class="pl-c1">===</span> '<span class="pl-s1">object</span>' ? result : newInstance);</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Create a new instance using function prototype.
var newInstance = Object.create(func.prototype)

// Call the function
var result = func.call(newInstance, x, y, z),

// If the result is a non-null object then use it otherwise just use the new instance.
console.log(result &amp;&amp; typeof result === 'object' ? result : newInstance);
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong>ES6 Class syntax:</strong></p>
<p dir="auto">ES6 introduces class feature to create the objects</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">class</span> <span class="pl-v">Person</span> <span class="pl-kos">{</span>
   <span class="pl-en">constructor</span><span class="pl-kos">(</span><span class="pl-s1">name</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
      <span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">name</span> <span class="pl-c1">=</span> <span class="pl-s1">name</span><span class="pl-kos">;</span>
   <span class="pl-kos">}</span>
<span class="pl-kos">}</span>

<span class="pl-k">var</span> <span class="pl-s1">object</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Person</span><span class="pl-kos">(</span><span class="pl-s">"Sudheer"</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="class Person {
   constructor(name) {
      this.name = name;
   }
}

var object = new Person(&quot;Sudheer&quot;);
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><strong>Singleton pattern:</strong></p>
<p dir="auto">A Singleton is an object which can only be instantiated one time. Repeated calls to its constructor return the same instance and this way one can ensure that they don't accidentally create multiple instances.</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">var</span> <span class="pl-s1">object</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
   <span class="pl-smi">this</span><span class="pl-kos">.</span><span class="pl-c1">name</span> <span class="pl-c1">=</span> <span class="pl-s">"Sudheer"</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="var object = new function(){
   this.name = &quot;Sudheer&quot;;
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
</ol>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-purpose-of-the-array-slice-method" class="anchor" aria-hidden="true" href="#what-is-the-purpose-of-the-array-slice-method"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the purpose of the array slice method</h3>
<p dir="auto">The <strong>slice()</strong> method returns the selected elements in an array as a new array object. It selects the elements starting at the given start argument, and ends at the given optional end argument without including the last element. If you omit the second argument then it selects till the end.</p>
<p dir="auto">Some of the examples of this method are,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">let</span> <span class="pl-s1">arrayIntegers</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">,</span> <span class="pl-c1">4</span><span class="pl-kos">,</span> <span class="pl-c1">5</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">let</span> <span class="pl-s1">arrayIntegers1</span> <span class="pl-c1">=</span> <span class="pl-s1">arrayIntegers</span><span class="pl-kos">.</span><span class="pl-en">slice</span><span class="pl-kos">(</span><span class="pl-c1">0</span><span class="pl-kos">,</span><span class="pl-c1">2</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// returns [1,2]</span>
<span class="pl-k">let</span> <span class="pl-s1">arrayIntegers2</span> <span class="pl-c1">=</span> <span class="pl-s1">arrayIntegers</span><span class="pl-kos">.</span><span class="pl-en">slice</span><span class="pl-kos">(</span><span class="pl-c1">2</span><span class="pl-kos">,</span><span class="pl-c1">3</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// returns [3]</span>
<span class="pl-k">let</span> <span class="pl-s1">arrayIntegers3</span> <span class="pl-c1">=</span> <span class="pl-s1">arrayIntegers</span><span class="pl-kos">.</span><span class="pl-en">slice</span><span class="pl-kos">(</span><span class="pl-c1">4</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//returns [5]</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="let arrayIntegers = [1, 2, 3, 4, 5];
let arrayIntegers1 = arrayIntegers.slice(0,2); // returns [1,2]
let arrayIntegers2 = arrayIntegers.slice(2,3); // returns [3]
let arrayIntegers3 = arrayIntegers.slice(4); //returns [5]
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong>Note:</strong> Slice method won't mutate the original array but it returns the subset as a new array.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-purpose-of-the-array-splice-method" class="anchor" aria-hidden="true" href="#what-is-the-purpose-of-the-array-splice-method"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the purpose of the array splice method</h3>
<p dir="auto">The <strong>splice()</strong> method is used either adds/removes items to/from an array, and then returns the removed item. The first argument specifies the array position for insertion or deletion whereas the optional second argument indicates the number of elements to be deleted. Each additional argument is added to the array.</p>
<p dir="auto">Some of the examples of this method are,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">let</span> <span class="pl-s1">arrayIntegersOriginal1</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">,</span> <span class="pl-c1">4</span><span class="pl-kos">,</span> <span class="pl-c1">5</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">let</span> <span class="pl-s1">arrayIntegersOriginal2</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">,</span> <span class="pl-c1">4</span><span class="pl-kos">,</span> <span class="pl-c1">5</span><span class="pl-kos">]</span><span class="pl-kos">;</span>
<span class="pl-k">let</span> <span class="pl-s1">arrayIntegersOriginal3</span> <span class="pl-c1">=</span> <span class="pl-kos">[</span><span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-c1">2</span><span class="pl-kos">,</span> <span class="pl-c1">3</span><span class="pl-kos">,</span> <span class="pl-c1">4</span><span class="pl-kos">,</span> <span class="pl-c1">5</span><span class="pl-kos">]</span><span class="pl-kos">;</span>

<span class="pl-k">let</span> <span class="pl-s1">arrayIntegers1</span> <span class="pl-c1">=</span> <span class="pl-s1">arrayIntegersOriginal1</span><span class="pl-kos">.</span><span class="pl-en">splice</span><span class="pl-kos">(</span><span class="pl-c1">0</span><span class="pl-kos">,</span><span class="pl-c1">2</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// returns [1, 2]; original array: [3, 4, 5]</span>
<span class="pl-k">let</span> <span class="pl-s1">arrayIntegers2</span> <span class="pl-c1">=</span> <span class="pl-s1">arrayIntegersOriginal2</span><span class="pl-kos">.</span><span class="pl-en">splice</span><span class="pl-kos">(</span><span class="pl-c1">3</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// returns [4, 5]; original array: [1, 2, 3]</span>
<span class="pl-k">let</span> <span class="pl-s1">arrayIntegers3</span> <span class="pl-c1">=</span> <span class="pl-s1">arrayIntegersOriginal3</span><span class="pl-kos">.</span><span class="pl-en">splice</span><span class="pl-kos">(</span><span class="pl-c1">3</span><span class="pl-kos">,</span> <span class="pl-c1">1</span><span class="pl-kos">,</span> <span class="pl-s">"a"</span><span class="pl-kos">,</span> <span class="pl-s">"b"</span><span class="pl-kos">,</span> <span class="pl-s">"c"</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//returns [4]; original array: [1, 2, 3, "a", "b", "c", 5]</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];

let arrayIntegers1 = arrayIntegersOriginal1.splice(0,2); // returns [1, 2]; original array: [3, 4, 5]
let arrayIntegers2 = arrayIntegersOriginal2.splice(3); // returns [4, 5]; original array: [1, 2, 3]
let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, &quot;a&quot;, &quot;b&quot;, &quot;c&quot;); //returns [4]; original array: [1, 2, 3, &quot;a&quot;, &quot;b&quot;, &quot;c&quot;, 5]
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong>Note:</strong> Splice method modifies the original array and returns the deleted array.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-difference-between-slice-and-splice" class="anchor" aria-hidden="true" href="#what-is-the-difference-between-slice-and-splice"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the difference between slice and splice</h3>
<p dir="auto">Some of the major difference in a tabular form</p>
<table>
<thead>
<tr>
<th>Slice</th>
<th>Splice</th>
</tr>
</thead>
<tbody>
<tr>
<td>Doesn't modify the original array(immutable)</td>
<td>Modifies the original array(mutable)</td>
</tr>
<tr>
<td>Returns the subset of original array</td>
<td>Returns the deleted elements as array</td>
</tr>
<tr>
<td>Used to pick the elements from array</td>
<td>Used to insert or delete elements to/from array</td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-a-higher-order-function" class="anchor" aria-hidden="true" href="#what-is-a-higher-order-function"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is a higher order function</h3>
<p dir="auto">Higher-order function is a function that accepts another function as an argument or returns a function as a return value or both.</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">const</span> <span class="pl-en">firstOrderFunc</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span> <span class="pl-kos">(</span><span class="pl-s">'Hello, I am a First order function'</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-en">higherOrder</span> <span class="pl-c1">=</span> <span class="pl-v">ReturnFirstOrderFunc</span> <span class="pl-c1">=&gt;</span> <span class="pl-v">ReturnFirstOrderFunc</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-en">higherOrder</span><span class="pl-kos">(</span><span class="pl-en">firstOrderFunc</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="const firstOrderFunc = () => console.log ('Hello, I am a First order function');
const higherOrder = ReturnFirstOrderFunc => ReturnFirstOrderFunc();
higherOrder(firstOrderFunc);
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-currying-function" class="anchor" aria-hidden="true" href="#what-is-the-currying-function"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the currying function</h3>
<p dir="auto">Currying is the process of taking a function with multiple arguments and turning it into a sequence of functions each with only a single argument. Currying is named after a mathematician <strong>Haskell Curry</strong>. By applying currying, a n-ary function turns it into a unary function.</p>
<p dir="auto">Let's take an example of n-ary function and how it turns into a currying function,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">const</span> <span class="pl-en">multiArgFunction</span> <span class="pl-c1">=</span> <span class="pl-kos">(</span><span class="pl-s1">a</span><span class="pl-kos">,</span> <span class="pl-s1">b</span><span class="pl-kos">,</span> <span class="pl-s1">c</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">+</span> <span class="pl-s1">b</span> <span class="pl-c1">+</span> <span class="pl-s1">c</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-en">multiArgFunction</span><span class="pl-kos">(</span><span class="pl-c1">1</span><span class="pl-kos">,</span><span class="pl-c1">2</span><span class="pl-kos">,</span><span class="pl-c1">3</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span><span class="pl-c">// 6</span>

<span class="pl-k">const</span> <span class="pl-en">curryUnaryFunction</span> <span class="pl-c1">=</span> <span class="pl-s1">a</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">b</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">c</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">a</span> <span class="pl-c1">+</span> <span class="pl-s1">b</span> <span class="pl-c1">+</span> <span class="pl-s1">c</span><span class="pl-kos">;</span>
<span class="pl-en">curryUnaryFunction</span> <span class="pl-kos">(</span><span class="pl-c1">1</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// returns a function: b =&gt; c =&gt;  1 + b + c</span>
<span class="pl-en">curryUnaryFunction</span> <span class="pl-kos">(</span><span class="pl-c1">1</span><span class="pl-kos">)</span> <span class="pl-kos">(</span><span class="pl-c1">2</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// returns a function: c =&gt; 3 + c</span>
<span class="pl-en">curryUnaryFunction</span> <span class="pl-kos">(</span><span class="pl-c1">1</span><span class="pl-kos">)</span> <span class="pl-kos">(</span><span class="pl-c1">2</span><span class="pl-kos">)</span> <span class="pl-kos">(</span><span class="pl-c1">3</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// returns the number 6</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="const multiArgFunction = (a, b, c) => a + b + c;
console.log(multiArgFunction(1,2,3));// 6

const curryUnaryFunction = a => b => c => a + b + c;
curryUnaryFunction (1); // returns a function: b => c =>  1 + b + c
curryUnaryFunction (1) (2); // returns a function: c => 3 + c
curryUnaryFunction (1) (2) (3); // returns the number 6
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">Curried functions are great to improve <strong>code reusability</strong> and <strong>functional composition</strong>.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-difference-between-let-and-var" class="anchor" aria-hidden="true" href="#what-is-the-difference-between-let-and-var"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the difference between let and var</h3>
<p dir="auto">You can list out the differences in a tabular format</p>
<table>
<thead>
<tr>
<th>var</th>
<th>let</th>
</tr>
</thead>
<tbody>
<tr>
<td>It is been available from the beginning of JavaScript</td>
<td>Introduced as part of ES6</td>
</tr>
<tr>
<td>It has function scope</td>
<td>It has block scope</td>
</tr>
<tr>
<td>Variables will be hoisted</td>
<td>Hoisted but not initialized</td>
</tr>
</tbody>
</table>
<p dir="auto">Let's take an example to see the difference,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">function</span> <span class="pl-en">userDetails</span><span class="pl-kos">(</span><span class="pl-s1">username</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
   <span class="pl-k">if</span><span class="pl-kos">(</span><span class="pl-s1">username</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
     <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">salary</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// undefined due to hoisting</span>
     <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">age</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// ReferenceError: Cannot access 'age' before initialization</span>
     <span class="pl-k">let</span> <span class="pl-s1">age</span> <span class="pl-c1">=</span> <span class="pl-c1">30</span><span class="pl-kos">;</span>
     <span class="pl-k">var</span> <span class="pl-s1">salary</span> <span class="pl-c1">=</span> <span class="pl-c1">10000</span><span class="pl-kos">;</span>
   <span class="pl-kos">}</span>
   <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">salary</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//10000 (accessible to due function scope)</span>
   <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">age</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//error: age is not defined(due to block scope)</span>
<span class="pl-kos">}</span>
<span class="pl-en">userDetails</span><span class="pl-kos">(</span><span class="pl-s">'John'</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="function userDetails(username) {
   if(username) {
     console.log(salary); // undefined due to hoisting
     console.log(age); // ReferenceError: Cannot access 'age' before initialization
     let age = 30;
     var salary = 10000;
   }
   console.log(salary); //10000 (accessible to due function scope)
   console.log(age); //error: age is not defined(due to block scope)
}
userDetails('John');
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-hoisting" class="anchor" aria-hidden="true" href="#what-is-hoisting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is Hoisting</h3>
<p dir="auto">Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution. Remember that JavaScript only hoists declarations, not initialisation.
Let's take a simple example of variable hoisting,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">message</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//output : undefined</span>
<span class="pl-k">var</span> <span class="pl-s1">message</span> <span class="pl-c1">=</span> <span class="pl-s">'The variable Has been hoisted'</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="console.log(message); //output : undefined
var message = 'The variable Has been hoisted';
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">The above code looks like as below to the interpreter,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">var</span> <span class="pl-s1">message</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">message</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">message</span> <span class="pl-c1">=</span> <span class="pl-s">'The variable Has been hoisted'</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="var message;
console.log(message);
message = 'The variable Has been hoisted';
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-are-closures" class="anchor" aria-hidden="true" href="#what-are-closures"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are closures</h3>
<p dir="auto">A closure is the combination of a function and the lexical environment within which that function was declared. i.e, It is an inner function that has access to the outer or enclosing function’s variables. The closure has three scope chains</p>
<ol dir="auto">
<li>Own scope where variables defined between its curly brackets</li>
<li>Outer function’s variables</li>
<li>Global variables</li>
</ol>
<p dir="auto">Let's take an example of closure concept,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">function</span> <span class="pl-v">Welcome</span><span class="pl-kos">(</span><span class="pl-s1">name</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
  <span class="pl-k">var</span> <span class="pl-en">greetingInfo</span> <span class="pl-c1">=</span> <span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">message</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
   <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">message</span><span class="pl-c1">+</span><span class="pl-s">' '</span><span class="pl-c1">+</span><span class="pl-s1">name</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
  <span class="pl-kos">}</span>
<span class="pl-k">return</span> <span class="pl-en">greetingInfo</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>
<span class="pl-k">var</span> <span class="pl-s1">myFunction</span> <span class="pl-c1">=</span> <span class="pl-v">Welcome</span><span class="pl-kos">(</span><span class="pl-s">'John'</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-s1">myFunction</span><span class="pl-kos">(</span><span class="pl-s">'Welcome '</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//Output: Welcome John</span>
<span class="pl-s1">myFunction</span><span class="pl-kos">(</span><span class="pl-s">'Hello Mr.'</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">//output: Hello Mr.John</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="function Welcome(name){
  var greetingInfo = function(message){
   console.log(message+' '+name);
  }
return greetingInfo;
}
var myFunction = Welcome('John');
myFunction('Welcome '); //Output: Welcome John
myFunction('Hello Mr.'); //output: Hello Mr.John
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">As per the above code, the inner function(i.e, greetingInfo) has access to the variables in the outer function scope(i.e, Welcome) even after the outer function has returned.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-a-service-worker" class="anchor" aria-hidden="true" href="#what-is-a-service-worker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is a service worker</h3>
<p dir="auto">A Service worker is basically a script (JavaScript file) that runs in the background, separate from a web page and provides features that don't need a web page or user interaction. Some of the major features of service workers are Rich offline experiences(offline first web application development), periodic background syncs, push notifications, intercept and handle network requests and programmatically managing a cache of responses.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-are-the-differences-between-cookie-local-storage-and-session-storage" class="anchor" aria-hidden="true" href="#what-are-the-differences-between-cookie-local-storage-and-session-storage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are the differences between cookie, local storage and session storage</h3>
<p dir="auto">Below are some of the differences between cookie, local storage and session storage,</p>
<table>
<thead>
<tr>
<th>Feature</th>
<th>Cookie</th>
<th>Local storage</th>
<th>Session storage</th>
</tr>
</thead>
<tbody>
<tr>
<td>Accessed on client or server side</td>
<td>Both server-side &amp; client-side</td>
<td>client-side only</td>
<td>client-side only</td>
</tr>
<tr>
<td>Lifetime</td>
<td>As configured using Expires option</td>
<td>until deleted</td>
<td>until tab is closed</td>
</tr>
<tr>
<td>SSL support</td>
<td>Supported</td>
<td>Not supported</td>
<td>Not supported</td>
</tr>
<tr>
<td>Maximum data size</td>
<td>4KB</td>
<td>5 MB</td>
<td>5MB</td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-main-difference-between-localstorage-and-sessionstorage" class="anchor" aria-hidden="true" href="#what-is-the-main-difference-between-localstorage-and-sessionstorage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the main difference between localStorage and sessionStorage</h3>
<p dir="auto">LocalStorage is the same as SessionStorage but it persists the data even when the browser is closed and reopened(i.e it has no expiration time) whereas in sessionStorage data gets cleared when the page session ends.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-a-promise" class="anchor" aria-hidden="true" href="#what-is-a-promise"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is a promise</h3>
<p dir="auto">A promise is an object that may produce a single value some time in the future with either a resolved value or a reason that it’s not resolved(for example, network error). It will be in one of the 3 possible states: fulfilled, rejected, or pending.</p>
<p dir="auto">The syntax of Promise creation looks like below,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre>    <span class="pl-k">const</span> <span class="pl-s1">promise</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Promise</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">resolve</span><span class="pl-kos">,</span> <span class="pl-s1">reject</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
      <span class="pl-c">// promise description</span>
    <span class="pl-kos">}</span><span class="pl-kos">)</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="    const promise = new Promise(function(resolve, reject) {
      // promise description
    })
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">The usage of a promise would be as below,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">const</span> <span class="pl-s1">promise</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">Promise</span><span class="pl-kos">(</span><span class="pl-s1">resolve</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>
  <span class="pl-en">setTimeout</span><span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>
    <span class="pl-en">resolve</span><span class="pl-kos">(</span><span class="pl-s">"I'm a Promise!"</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
  <span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-c1">5000</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-s1">reject</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>

<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-s1">promise</span><span class="pl-kos">.</span><span class="pl-en">then</span><span class="pl-kos">(</span><span class="pl-s1">value</span> <span class="pl-c1">=&gt;</span> <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">value</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="const promise = new Promise(resolve => {
  setTimeout(() => {
    resolve(&quot;I'm a Promise!&quot;);
  }, 5000);
}, reject => {

});

promise.then(value => console.log(value));
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">The action flow of a promise will be as below,</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sudheerj/javascript-interview-questions/blob/master/images/promises.png"><img src="/sudheerj/javascript-interview-questions/raw/master/images/promises.png" alt="Screenshot" style="max-width: 100%;"></a></p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-a-callback-hell" class="anchor" aria-hidden="true" href="#what-is-a-callback-hell"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is a callback hell</h3>
<p dir="auto">Callback Hell is an anti-pattern with multiple nested callbacks which makes code hard to read and debug when dealing with asynchronous logic. The callback hell looks like below,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-en">async1</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
    <span class="pl-en">async2</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
        <span class="pl-en">async3</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
            <span class="pl-en">async4</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">{</span>
                ...<span class="pl-kos">.</span>
            <span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
        <span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
    <span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="async1(function(){
    async2(function(){
        async3(function(){
            async4(function(){
                ....
            });
        });
    });
});
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-promise-chaining" class="anchor" aria-hidden="true" href="#what-is-promise-chaining"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is promise chaining</h3>
<p dir="auto">The process of executing a sequence of asynchronous tasks one after another using promises is known as Promise chaining. Let's take an example of promise chaining for calculating the final result,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">new</span> <span class="pl-v">Promise</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">resolve</span><span class="pl-kos">,</span> <span class="pl-s1">reject</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>

  <span class="pl-en">setTimeout</span><span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">resolve</span><span class="pl-kos">(</span><span class="pl-c1">1</span><span class="pl-kos">)</span><span class="pl-kos">,</span> <span class="pl-c1">1000</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">then</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>

  <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 1</span>
  <span class="pl-k">return</span> <span class="pl-s1">result</span> <span class="pl-c1">*</span> <span class="pl-c1">2</span><span class="pl-kos">;</span>

<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">then</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>

  <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 2</span>
  <span class="pl-k">return</span> <span class="pl-s1">result</span> <span class="pl-c1">*</span> <span class="pl-c1">3</span><span class="pl-kos">;</span>

<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">.</span><span class="pl-en">then</span><span class="pl-kos">(</span><span class="pl-k">function</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>

  <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// 6</span>
  <span class="pl-k">return</span> <span class="pl-s1">result</span> <span class="pl-c1">*</span> <span class="pl-c1">4</span><span class="pl-kos">;</span>

<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="new Promise(function(resolve, reject) {

  setTimeout(() => resolve(1), 1000);

}).then(function(result) {

  console.log(result); // 1
  return result * 2;

}).then(function(result) {

  console.log(result); // 2
  return result * 3;

}).then(function(result) {

  console.log(result); // 6
  return result * 4;

});
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">In the above handlers, the result is passed to the chain of .then() handlers with the below work flow,</p>
<ol dir="auto">
<li>The initial promise resolves in 1 second,</li>
<li>After that <code>.then</code> handler is called by logging the result(1) and then return a promise with the value of result * 2.</li>
<li>After that the value passed to the next <code>.then</code> handler by logging the result(2) and return a promise with result * 3.</li>
<li>Finally the value passed to the last <code>.then</code> handler by logging the result(6) and return a promise with result * 4.</li>
</ol>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-promiseall" class="anchor" aria-hidden="true" href="#what-is-promiseall"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is promise.all</h3>
<p dir="auto">Promise.all is a promise that takes an array of promises as an input (an iterable), and it gets resolved when all the promises get resolved or any one of them gets rejected. For example, the syntax of promise.all method is below,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-v">Promise</span><span class="pl-kos">.</span><span class="pl-en">all</span><span class="pl-kos">(</span><span class="pl-kos">[</span><span class="pl-v">Promise1</span><span class="pl-kos">,</span> <span class="pl-v">Promise2</span><span class="pl-kos">,</span> <span class="pl-v">Promise3</span><span class="pl-kos">]</span><span class="pl-kos">)</span> <span class="pl-kos">.</span><span class="pl-en">then</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-kos">{</span>   <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">result</span><span class="pl-kos">)</span> <span class="pl-kos">}</span><span class="pl-kos">)</span> <span class="pl-kos">.</span><span class="pl-en">catch</span><span class="pl-kos">(</span><span class="pl-s1">error</span> <span class="pl-c1">=&gt;</span> <span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s">`Error in promises <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-s1">error</span><span class="pl-kos">}</span></span>`</span><span class="pl-kos">)</span><span class="pl-kos">)</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Promise.all([Promise1, Promise2, Promise3]) .then(result) => {   console.log(result) }) .catch(error => console.log(`Error in promises ${error}`))
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong>Note:</strong> Remember that the order of the promises(output the result) is maintained as per input order.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-a-strict-mode-in-javascript" class="anchor" aria-hidden="true" href="#what-is-a-strict-mode-in-javascript"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is a strict mode in javascript</h3>
<p dir="auto">Strict Mode is a new feature in ECMAScript 5 that allows you to place a program, or a function, in a “strict” operating context. This way it prevents certain actions from being taken and throws more exceptions. The literal expression <code>"use strict";</code> instructs the browser to use the javascript code in the Strict mode.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-how-do-you-declare-strict-mode" class="anchor" aria-hidden="true" href="#how-do-you-declare-strict-mode"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>How do you declare strict mode</h3>
<p dir="auto">The strict mode is declared by adding "use strict"; to the beginning of a script or a function.
If declared at the beginning of a script, it has global scope.</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-s">"use strict"</span><span class="pl-kos">;</span>
<span class="pl-s1">x</span> <span class="pl-c1">=</span> <span class="pl-c1">3.14</span><span class="pl-kos">;</span> <span class="pl-c">// This will cause an error because x is not declared</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="&quot;use strict&quot;;
x = 3.14; // This will cause an error because x is not declared
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">and if you declare inside a function, it has local scope</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-s1">x</span> <span class="pl-c1">=</span> <span class="pl-c1">3.14</span><span class="pl-kos">;</span>       <span class="pl-c">// This will not cause an error.</span>
<span class="pl-en">myFunction</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-k">function</span> <span class="pl-en">myFunction</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
  <span class="pl-s">"use strict"</span><span class="pl-kos">;</span>
  <span class="pl-s1">y</span> <span class="pl-c1">=</span> <span class="pl-c1">3.14</span><span class="pl-kos">;</span>   <span class="pl-c">// This will cause an error</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="x = 3.14;       // This will not cause an error.
myFunction();

function myFunction() {
  &quot;use strict&quot;;
  y = 3.14;   // This will cause an error
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-difference-between-null-and-undefined" class="anchor" aria-hidden="true" href="#what-is-the-difference-between-null-and-undefined"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the difference between null and undefined</h3>
<p dir="auto">Below are the main differences between null and undefined,</p>
<table>
<thead>
<tr>
<th>Null</th>
<th>Undefined</th>
</tr>
</thead>
<tbody>
<tr>
<td>It is an assignment value which indicates that variable points to no object.</td>
<td>It is not an assignment value where a variable has been declared but has not yet been assigned a value.</td>
</tr>
<tr>
<td>Type of null is object</td>
<td>Type of undefined is undefined</td>
</tr>
<tr>
<td>The null value is a primitive value that represents the null, empty, or non-existent reference.</td>
<td>The undefined value is a primitive value used when a variable has not been assigned a value.</td>
</tr>
<tr>
<td>Indicates the absence of a value for a variable</td>
<td>Indicates absence of variable itself</td>
</tr>
<tr>
<td>Converted to zero (0) while performing primitive operations</td>
<td>Converted to NaN while performing primitive operations</td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-are-the-pros-and-cons-of-promises-over-callbacks" class="anchor" aria-hidden="true" href="#what-are-the-pros-and-cons-of-promises-over-callbacks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What are the pros and cons of promises over callbacks</h3>
<p dir="auto">Below are the list of pros and cons of promises over callbacks,</p>
<p dir="auto"><strong>Pros:</strong></p>
<ol dir="auto">
<li>It avoids callback hell which is unreadable</li>
<li>Easy to write sequential asynchronous code with .then()</li>
<li>Easy to write parallel asynchronous code with Promise.all()</li>
<li>Solves some of the common problems of callbacks(call the callback too late, too early, many times and swallow errors/exceptions)</li>
</ol>
<p dir="auto"><strong>Cons:</strong></p>
<ol dir="auto">
<li>It makes little complex code</li>
<li>You need to load a polyfill if ES6 is not supported</li>
</ol>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-the-difference-between-an-attribute-and-a-property" class="anchor" aria-hidden="true" href="#what-is-the-difference-between-an-attribute-and-a-property"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is the difference between an attribute and a property</h3>
<p dir="auto">Attributes are defined on the HTML markup whereas properties are defined on the DOM. For example, the below HTML element has 2 attributes type and value,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-c1">&lt;</span><span class="pl-ent">input</span> <span class="pl-c1">type</span><span class="pl-c1">=</span><span class="pl-s">"text"</span> <span class="pl-c1">value</span><span class="pl-c1">=</span><span class="pl-s">"Name:"</span><span class="pl-c1">&gt;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="<input type=&quot;text&quot; value=&quot;Name:&quot;>
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">You can retrieve the attribute value as below,</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">const</span> <span class="pl-s1">input</span> <span class="pl-c1">=</span> <span class="pl-smi">document</span><span class="pl-kos">.</span><span class="pl-en">querySelector</span><span class="pl-kos">(</span><span class="pl-s">'input'</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">input</span><span class="pl-kos">.</span><span class="pl-en">getAttribute</span><span class="pl-kos">(</span><span class="pl-s">'value'</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// Good morning</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">input</span><span class="pl-kos">.</span><span class="pl-c1">value</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// Good morning</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="const input = document.querySelector('input');
console.log(input.getAttribute('value')); // Good morning
console.log(input.value); // Good morning
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">And after you change the value of the text field to "Good evening", it becomes like</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">input</span><span class="pl-kos">.</span><span class="pl-en">getAttribute</span><span class="pl-kos">(</span><span class="pl-s">'value'</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// Good morning</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s1">input</span><span class="pl-kos">.</span><span class="pl-c1">value</span><span class="pl-kos">)</span><span class="pl-kos">;</span> <span class="pl-c">// Good evening</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="console.log(input.getAttribute('value')); // Good morning
console.log(input.value); // Good evening
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-an-event-loop" class="anchor" aria-hidden="true" href="#what-is-an-event-loop"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is an event loop</h3>
<p dir="auto">The Event Loop is a queue of callback functions. When an async function executes, the callback function is pushed into the queue. The JavaScript engine doesn't start processing the event loop until the async function has finished executing the code.
<strong>Note:</strong> It allows Node.js to perform non-blocking I/O operations even though JavaScript is single-threaded.</p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>
<li>
<h3 dir="auto"><a id="user-content-what-is-call-stack" class="anchor" aria-hidden="true" href="#what-is-call-stack"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is call stack</h3>
<p dir="auto">Call Stack is a data structure for javascript interpreters to keep track of function calls in the program. It has two major actions,</p>
<ol dir="auto">
<li>Whenever you call a function for its execution, you are pushing it to the stack.</li>
<li>Whenever the execution is completed, the function is popped out of the stack.</li>
</ol>
<p dir="auto">Let's take an example and it's state representation in a diagram format</p>
<div class="highlight highlight-source-js position-relative overflow-auto"><pre><span class="pl-k">function</span> <span class="pl-en">hungry</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
   <span class="pl-en">eatFruits</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>
<span class="pl-k">function</span> <span class="pl-en">eatFruits</span><span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-kos">{</span>
   <span class="pl-k">return</span> <span class="pl-s">"I'm eating fruits"</span><span class="pl-kos">;</span>
<span class="pl-kos">}</span>

<span class="pl-c">// Invoke the `hungry` function</span>
<span class="pl-en">hungry</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="function hungry() {
   eatFruits();
}
function eatFruits() {
   return &quot;I'm eating fruits&quot;;
}

// Invoke the `hungry` function
hungry();
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">The above code  processed in a call stack as  below,</p>
<ol dir="auto">
<li>Add the <code>hungry()</code> function to the call stack list and execute the code.</li>
<li>Add the <code>eatFruits()</code> function to the call stack list and execute the code.</li>
<li>Delete the <code>eatFruits()</code> function from our call stack list.</li>
<li>Delete the <code>hungry()</code> function from the call stack list since there are no items anymore.</li>
</ol>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sudheerj/javascript-interview-questions/blob/master/images/call-stack.png"><img src="/sudheerj/javascript-interview-questions/raw/master/images/call-stack.png" alt="Screenshot" style="max-width: 100%;"></a></p>
<p dir="auto"><strong><a href="#table-of-contents"><g-emoji class="g-emoji" alias="arrow_up" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2b06.png">⬆</g-emoji> Back to Top</a></strong></p>
</li>

</ol>
