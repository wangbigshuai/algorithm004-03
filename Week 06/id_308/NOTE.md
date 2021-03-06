## 字典树和并查集

#### 字典树

- 字典树，即Trie树，又称单词查找树或键树，是一种树形结构。典型应用是用于统计和排序大量的字符串（但不仅限于字符串），所以经常被搜索引擎系统用于文本词频统计。
- 它的优点是：最大限度的减少无谓的字符串比较，查询效率比哈希表高
- 基本性质
    * 结点本身不存完整单词
    * 从根结点到某一结点，路径上经过的字符串连接起来，为该结点对应的字符串
    * 每个结点的所有子结点路径代表的字符都不相同
- 核心思想
    * Trie树的核心思想是空间换时间
    * 利用字符串的公共前缀来降低查询时间的开销以达到提高效率的目的。
    
#### 并查集

- 组团、配对问题
- 基本操作
    * makeSet(s): 建立一个新的并查集，其中包含S个单元素集合
    * unionSet(x,y): 把元素x和元素y所在的并查集合并，要求x和y所在的集合不相交，如果相交则不合并
    * find(x): 找到元素x所在的集合的代表，该操作也可以用于判断两个元素是否位于同一集合，只要将它们各自的代表比较一下就可以了


## 高级搜索

#### 剪枝的实现和特性

- 初级搜索
    * 朴素搜索
    * 优化方式:不重复(fibonacci)/剪枝(生成括号问题)
    * 搜索方向
        - DFS: 深度优先搜索
        - BFS: 广度优先搜索
        - 双向搜索/启发式搜索


#### 双向BFS的实现/特性和题解


#### 高级树/AVL/红黑树
