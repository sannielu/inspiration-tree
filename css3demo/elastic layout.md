#弹性布局#

	
	.flex{
	  display: -webkit-box;/* android 2.1-3.0, ios 3.2-4.3 */
	  display: -webkit-flex; /* Chrome 21+ */
	  display: -ms-flexbox; /* WP IE 10 */
	  display: flex; /* android 4.4 */
	  display:box;/* uc */
	}
	.flex-pack-justify{
	/* 水平布局下的子元素 2端对齐 */
	  -webkit-box-pack:justify;
	  -webkit-justify-content:space-between;
	  -ms-flex-pack:justify;
	  justify-content:space-between;
	}
	.flex-1{
	  -webkit-box-flex:1;
	  -webkit-flex:1;
	  -ms-flex:1;
	  flex:1;
	}
	.flex-align-center{
	    /* 水平布局下的子元素 垂直居中 */
	    -webkit-box-align: center;/* android 2.1-3.0, ios 3.2-4.3 */
	    -webkit-align-items: center;/* Chrome 21+ */
	    -ms-flex-align: center;/* WP IE 10 */
	    align-items: center;/* android 4.4 */
	}
	.flex-pack-center{
	    /* 水平布局下的子元素 水平居中 */
	    -webkit-box-pack: center;/* android 2.1-3.0, ios 3.2-4.3 */
	    -webkit-justify-content: center;/* Chrome 21+ */
	    -ms-flex-pack: center;/* WP IE 10 */
	    justify-content: center;/* android 4.4 */
	}
	.flex-direction-column{  
	    /*  盒模型垂直布局  */
	    -webkit-box-orient: vertical;
	    -webkit-flex-direction: column;
	    -ms-flex-direction: column;
	    flex-direction: column;
	}
	
