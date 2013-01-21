---
layout: post
tags : [jekyll, markdown, syntax highlighting]
image: http://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/HTML_source_code_example.svg/315px-HTML_source_code_example.svg.png
---

I am testing syntax highlighting in this Jekyll blog.

    public class Test
    {
    	public int Number { get; private set; }
	    
	    public Test(int number)
	    {
		    Number = number;
	    }
    }

{% highlight c# %}
public class Test
{
	public int Number { get; private set; }
	
	public Test(int number)
	{
		Number = number;
	}
}
{% endhighlight %}