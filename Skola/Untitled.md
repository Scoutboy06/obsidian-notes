/lib/get_mime_from_file_name.rb:
```ruby

MIME_TYPES = {
	...
}

def get_mime_from_file_name(file_name)
	file_type = file_name.split('.').last
	return MIME_TYPES[file_name]
end
```

/lib/tcp_server.rb:

```ruby
file_type = get_mime_from_file_name(request.resource.split('/').last)
```

