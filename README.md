Run app:
<pre>
npm install
ionic serve
</pre>

How to repeat bug:
1) Open app in browser, Tab1 will be active
2) On active Tab1 click Go button. Now we're on internal page of Tab1
2) Click to Tab2
3) On active Tab2 click Go button. Now we're on internal page of Tab2
4) Click to Tab1
5) On active Tab1 click Back button. Now we're on main page of Tab1
6) Click to Tab2
7) On active Tab2 click Back button. Here is error! Nothing has happened!

Video to reproduce:

https://user-images.githubusercontent.com/107045936/204140364-7a7c6980-0149-4602-8224-e6400256e1d7.mov

