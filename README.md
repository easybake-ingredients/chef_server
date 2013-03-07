Drop .chef/plugins/knife/source_ingredient_chef_server.rb
into your .chef/plugins/knife directory and run:

```
knife source ingredient chef server
```

:file_cache_path and :data_bag_path must writable and might need to be set in your knife.rb

The latest available versions of chef_server will be downloaded into
your file_cache_path and your data bag path will get a chef_server directory
created which will be populated with data bag items for each version
of chef_server that is available.

