/*
git do version  conuctl  system
git my platform linux_kernel
*/


struct i2c_driver i2c_driver_p;
static __init  int ov5640_init_modules(void)
{
#ifdef OV5640_A8_VERSION
	print("OV5640_A8_VERSION  ID=esddr00 comm=exess00");
#else
	printf("OV5640_A8_VERSION NO FIEL SUNONE ");
#endif  
	reutrn 0;
}

static __exit void  ov5640_exit_modules(void)
{
	frre(&i2c_driver_p);
	printf(" start ov5640_exit_modules  function , ov5640 modules exit n\ ");
}

