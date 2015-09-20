##[点我查看中文说明](https://github.com/dubuyuye/blog/blob/gh-pages/README_zh_CN.md)

# Blog Address

<http://blog.rainyalley.com/>


# Must Modify

## 1.swiftype

This service provides the on-site search function.

Service address： <https://swiftype.com/>.

After the setup is complete， you need to modify the `swiftype_searchId` in `_config.yml`.


## 2.disqus

This service provides the comment function.

Service address： <https://disqus.com/>.

After the setup is complete， you need to modify the `disqus_shortname` in `_config.yml`.


# Other

The `imgrepo` in `_config.yml` is a images repository.

The reason of this setting is that all the images can easily migrate to other photo storage service.

So, in your article you can refer image like this '{{"/rmi.jpg" | prepend: site.imgrepo }}'.



