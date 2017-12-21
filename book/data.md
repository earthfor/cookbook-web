## 菜谱聚合

1. 美食天下 eg: http://home.meishichina.com/search/recipe/青椒炒肉丝

> 特点： 比较全面，并且感觉上获取资源更容易，通用。获取喜欢，收藏数目API http://home.meishichina.com/ajax/ajax.php?ac=user&op=getrecipeloadinfo&id=菜单ID， 获取评论 http://home.meishichina.com/meishi2.php?ac=comment&op=clist&pageSize=15&page=1&orderBy=desc&isEdit=0&isDel=1&isReply=1&id=菜单ID&idtype=recipe

2. 心食谱 eg: https://www.xinshipu.com/doSearch.html?q=青椒炒肉丝  然后跳转从 `header` 获得真实路径

> 特点： 有建议， API： https://www.xinshipu.com/doGetSuggestion.html?term=青椒炒肉丝, 需要加上 user-agent

3. 美食杰 eg: http://so.meishi.cc/index.php?q=青椒炒肉丝

> 特点： 有建议， API： http://so.meishi.cc/ajax/ajaxtitle.php?words=青椒炒肉丝, 页面简单，直接就能获取所有东西，不用进行ajax， 包括评论，而且属性还很全比如工艺，难度，口味标准等。

4. 下厨房 eg: https://www.xiachufang.com/search/?keyword=青椒炒肉丝 然后跳转从 `header` 获得真实路径

> 没建议，但是有用户展示模块，而且还挺不错的,eg: https://www.xiachufang.com/recipe/1043759/dishes/?page=1 后面page是页数。

5. 中国菜谱网 eg: http://www.chinacaipu.com/index/search?keyword=%E9%9D%92%E6%A4%92%E7%82%92%E8%82%89%E4%B8%9D

> 没建议，简简单单的。

6. 好豆网 eg: http://www.haodou.com/s?wd=青椒炒肉丝&tp=recipe

> 特点： 有评论，浏览数，点赞数。 需要花一点时间研究一下, 有排行榜 http://www.haodou.com/recipe/top/

7. 2345实用查询 eg: http://tools.2345.com/frame/menu/search?keyword=青椒炒肉丝

> 特点； 提供建议，eg: http://tools.2345.com/frame/menu/think?keyword=青椒炒肉丝
