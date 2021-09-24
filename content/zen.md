+++
Slug = "{{ $seed := .Filename }}{{ $random := delimit (shuffle (split (md5 $seed) \"\" )) \"\" }}{{ $random }}"
Title = "zen"
date = ""
draft = false

+++
