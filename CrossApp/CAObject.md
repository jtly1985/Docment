#CAObject

----------

**类说明**
	
CrossApp引擎的根类，主要是进行内存管理，定义部分回调函数指针。引擎绝大部分类派生自CAObject,其共同遵从同一套内存管理方式。


----------




**Public属性**

					CAObject(void)
	
	virtual			~CAObject(void)
	
			void	release(void)	

			void	retain(void)

		CAObject*	autorelease(void)
	
		CAObject*	copy(void)

			bool	isSingleReference(void) const
		
	unsigned int	retainCount(void)const

	virtual	void	update(float dt)

	
		 





