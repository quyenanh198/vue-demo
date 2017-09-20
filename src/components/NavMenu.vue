<template>
	<div class="header">
		<ul id="header">
	        <li><a href="#">Home</a></li>
	        <li>
	            <a href="#">Stories</a>
	            <ul class="hidden">
	                <li><a href="#">Roadtrip</a></li>
	                <li><a href="#">Life</a></li>
	            </ul>
	        </li>
	        <li>
	            <a href="#">Books</a>
	            <ul class="hidden">
	                <li><a href="#">Photography</a></li>
	                <li><a href="#">Web Development</a></li>
	                <li><a href="#">Drawing</a></li>
	            </ul>
	        </li>
	        <li><a href="#">News</a></li>
	        <li><a href="#">About me</a></li>
	    </ul>
    </div>
</template>


<!-- Javascript -->
<script>
export default {
  name: 'header',
  data () {
    return {
      blogName: 'Quyen Anh'
    }
  }
}
</script>


<!-- CSS -->
<style scoped>
	/*Strip the ul of padding and list styling*/
	ul {
	    list-style-type:none;
	    margin:0;
	    padding:0;
	    position: absolute;
	}
	/*Create a horizontal list with spacing*/
	li {
	    display:inline-block;
	    float: left;
	    margin-right: 1px;
	}

	/*Style for menu links*/
	li a {
	    display:block;
	    min-width:140px;
	    height: 50px;
	    text-align: center;
	    line-height: 50px;
	    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
	    color: #fff;
	    background: #2f3036;
	    text-decoration: none;
	}
	/*Hover state for top level links*/
	li:hover a {
	    background: #19c589;
	}
	/*Style for dropdown links*/
	li:hover ul a {
	    background: #f3f3f3;
	    color: #2f3036;
	    height: 40px;
	    line-height: 40px;
	}
	/*Hover state for dropdown links*/
	li:hover ul a:hover {
	    background: #19c589;
	    color: #fff;
	}

	/*Hide dropdown links until they are needed*/
	li ul {
	    display: none;
	}
	/*Make dropdown links vertical*/
	li ul li {
	    display: block;
	    float: none;
	}
	/*Prevent text wrapping*/
	li ul li a {
	    width: auto;
	    min-width: 100px;
	    padding: 0 20px;
	}
	/*Display the dropdown on hover*/
	ul li a:hover + .hidden, .hidden:hover {
	    display: block;
	}
</style>