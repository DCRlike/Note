## 初始化
```c++
struct dsu 
{
	vector<size_t> pa; 
	explicit dsu(size_t size) : pa(size) 
	{ iota(pa.begin(), pa.end(), 0); }
};
```

## 查询
