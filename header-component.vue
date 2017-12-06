<template>
    <header>
      <div class="container">
        <div class="row">
          <div class="col-xs-8 col-sm-12 col-md-4">
			      <a href="#/">
              <div class="brand" style="background-image:url('assets/media/svart-logo-205x65.jpg')"></div>
			      </a>
          </div>
          
          <div class="col-sm-12 col-md-8">
            <nav>
                <ul class="level-2">                    
                    <li>
                        <router-link :to="{name: 'contact'}">Kontakta oss</router-link>
                    </li>
                </ul>
            </nav>
          </div>
        </div>
      </div>

      <div id="toggle" class="toggle">
        <a href="#" class="cross"><span></span></a>
      </div>
    </header>
</template>
  
