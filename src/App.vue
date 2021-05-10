<template>
<div id="app">
    <div id="nav">
        <b-navbar toggleable="sm" type="light" variant="light">
            <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

            <b-navbar-brand>
                <img src="@/assets/pistar_logo_black.png" style="height:32px;width:32px" />
                <router-link to="/" class="ml-2">piSTAR Lab</router-link>
            </b-navbar-brand>

            <b-collapse id="nav-text-collapse" is-nav>
                <b-navbar-nav class="ml-auto">
                    <b-nav-item target="_blank" href="https://pistarlab.readthedocs.io/en/latest/plugins.html">
                        Plugins
                    </b-nav-item>

                    <b-nav-item target="_blank" href="http://pistarlab.readthedocs.io">
                        Documentation
                    </b-nav-item>
                    <b-nav-item href="http://github.com/pistarlab/pistarlab" title="github" target="_blank">
                      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
                                <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z" />
                            </svg>
                    </b-nav-item>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
    <router-view />
    <footer class="mt-5 pt-5 pb-5">
        <b-container fluid>
            <b-row class="justify-content-center">
                <b-col class="text-left">
                    <b-link href="http://pistarlab.org" class="ml-5"> <img src="@/assets/pistar_edit_w.png" style="height:32px;width:32px" /> pistarlab.org</b-link>

                </b-col>
                <b-col class="text-left">
                    <b-ul>
                        <b-li>

                            <b-link></b-link>

                        </b-li>
                    </b-ul>
                </b-col>
            </b-row>
        </b-container>

    </footer>
</div>
</template>

<style lang="scss">
.bam {
    background: rgb(2, 0, 36);
    background: linear-gradient(90deg, rgba(2, 0, 36, 1) 0%, rgba(241, 50, 97, 1) 44%, rgba(241, 50, 97, 0.648879620207458) 95%);
}

footer {
    background: #343e3c;
    color: #fff;
    padding-top: 20px;
}

footer a {
    color: #d8d8d8;;
}

footer a:hover {
    color: #fff
}

a {
    color: #343e3c;
}

a:hover {
    color: #343e3c;
}
</style>
