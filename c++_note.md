1.const用法
普通变量：const int a $\rightarrow$ 锁死数值。
指针：const int* (锁数据，指针可变) vs int* const (锁指针，数据可变)。
引用（最重要）：const Type& $\rightarrow$ 高效传参的标准写法（只读、不拷贝）。
成员函数：void func() const $\rightarrow$ 承诺函数内部不改动对象状态。
