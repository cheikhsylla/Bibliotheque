<template>
  <div>
		<div class="container">

			<h5 class="text-center">Welcome to Cheikh's Library</h5>

	</div>
	<div class="menu">
		<nav>
			<ul>
				<li> <a href="">AllBooks</a></li>
				<li> <a href="">Available_Books</a></li>
				<li> <a href="">Unavaible_Books</a></li>
			</ul>
		</nav>
	</div>
	
  </div>
</template>

<script>
export default {
	name: 'Navbar',
  

}
</script>

<style lang="scss">
.container {
    border: 1rem solid blue;
    background: white;
    margin-top: 13%;

    width: 50%;
    h5{
        color:red;
        text-transform: uppercase;


    }

}

.menu {
width:fit-content;
margin: 0 auto;
  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: blue;



  }

  li {
    float: left;

  }

  a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;

    &:hover {
      background-color: blue;
      color: red;
    }

  }

}
</style>

