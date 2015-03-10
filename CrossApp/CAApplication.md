## CAApplication

主要负责：控制应用程序的生命周期、提供和管理一些全局的资源、处理交互事件、绘制界面

----
public

virtual bool init(void)
	
virtual long getClassTypeInfo()

inline CAWindow* getRootWindow(void)

inline double getAnimationInterval(void)

virtual void setAnimationInterval(double dValue)

inline bool isDisplayStats(void)

inline void setDisplayStats(bool bDisplayStats)	

inline float getSecondsPerFrame()

inline CCEGLView* getOpenGLView(void)

void setOpenGLView(CCEGLView* pobOpenGLView)

inline bool isNextDeltaTimeZero(void)

void setNextDeltaTimezero(bool bNextDeltaTimeZero)

inline bool isPaused(void)

inline unsigned int getTotaFrames(void)

