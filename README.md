# RefreshLayout

# Add it in your root build.gradle at the end of repositories:
    allprojects{
        positories {
            ..
            maven{
                url 'https://jitpack.io'
                }
            }
         }
# Step 2. Add the dependency
    dependencies{
         compile 'com.github.theyoungl:FlexSlider:V1.0'
    }
