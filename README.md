This project is useful to syntax highlight code snippets. 

1. Run the app, use markdown to specify the language to use for syntax highlighting. For instance, to use Ruby:

```ruby
class Stack
  def initialize
    @elements = []
  end
  
  def push(element)
    @elements << element
  end  
end
```

2. Use Chrome browser to view the snippet show page, copy the code and paste it in blog hosted on blogger for instance.
3. Your blog posts will now be syntax highlighted. 

Here is an example blog post that shows what it looks like: http://www.rubyplus.net/2016/09/implemenation-aware-client-and-data.html

## Why not use gist provided by github?

Because, if you copy paste syntax highlighted code using gist to blogger, you will be wrestling with aligning the code in the editor. This Rails 5 app, it's just one click and paste and you are done!

## Why not use pastie?

I tried to test it, but pastie was down! It gave the following error message.

Error 503 Service Unavailable
Service Unavailable
Guru Meditation:

XID: 1853192589

Varnish cache server

## Do you have any plans of offering this as a service?

Yes, it will soon be available on www.rubyplus.com so that you can copy paste the code to your blog without having to deploy this code or run it locally.

## Known Issues

Using rhtml in the markdown can result truncated html code in the blog post. If you want to display pure Ruby code, this will work.