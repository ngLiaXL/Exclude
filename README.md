# Exclude

If you have some sources that you don't want to be compiled, you have to declare a filter for the sources
    sourceSets {
        main {
            java {
                exclude 'com/ldroid/exclude/exc/**'
            }
        }
    }
