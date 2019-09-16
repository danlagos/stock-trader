<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div>
            <button><router-link to="/">Stock Trader</router-link></button>
            <button><router-link to="/portfolio" activeClass="active"><a>Portfolio</a></router-link></button>
            <button><router-link to="/stocks" activeClass="active"><a>Stocks</a></router-link></button>
        </div>
        <button>End Day</button>

        <div class="dropdown">
            <a 
                class="btn btn-secondary dropdown-toggle" 
                href="#" role="button" 
                id="dropdownMenuLink" 
                data-toggle="dropdown" 
                aria-haspopup="true" 
                aria-expanded="false">
                Save & Load <span class='caret'></span>
            </a>

            <div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                <ul>
                    <li><a class="dropdown-item" href="#">Save Data</a></li>
                    <li><a class="dropdown-item" href="#">Load Data</a></li>
                </ul>
            </div>
        </div>           


    </nav>
</template>