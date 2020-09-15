# AllurePluginTask
Creation of simple plugin for allure

# Setup:
1. Run <code>gradle toJar</code>
2. Copy <code>./build/libs/my-custom-logo-plugin-2.13.0.jar</code> to <code>./src/dist</code>
3. Copy <code>./src/dist</code> package to path <code>.../allure-commandline/dist/plugins</code>. Rename this <code>"dist"</code> package to <code>"my-custom-logo-plugin"</code>
4. Edit file <code>.../allure-commandline/dist/config/allure.yml</code>. Add <code>  - my-custom-logo-plugin</code> at the end of the file.
5. Run <code>allure serve allure-results</code>
