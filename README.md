# SF Examination - Test App 

[Miro Board](https://miro.com/app/board/uXjVMQNHXGo=/) 

## Migration Steps
1. Checkout on master branch first. This is our main space of where source code of the app is

    ![image](https://user-images.githubusercontent.com/110352438/234299651-aa55756f-f0ac-4124-858d-fd8fd732bf2b.png)

2. Perform ```git pull``` in order to sync your local files with contents of master branch

    ![image](https://user-images.githubusercontent.com/110352438/234299928-406b907d-7c14-48e0-96cd-bf0f54b52347.png)

3. Create your feature specific branch

    - Click on your current branch (should be master)
    - Select 'Create New Branch' from the pallette
    - Provide Branch Name
    - Press Enter

4. Branch Name Convention

    - New Feature
    feature/US

   - Bugfix
   bugfix/US
   
5. Publish your branch

    ![image](https://user-images.githubusercontent.com/110352438/234302795-7cc2499a-8b87-455f-8d7b-96c33b24b54a.png)

   
6. Pull your changes by building a [package.xml](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/manifest_samples.htm) in Manifest folder

7. Retrieve changes from your current org by clicking 'Retrieve Source in Manifest from Org'

    ![image](https://user-images.githubusercontent.com/110352438/234303161-bd2e8ebc-4a5f-433c-ba0f-5337c9994b72.png)

8. Stage your changes one by one in 'Source Control' tab in VS Code. This will ensure that your next command, commit, will have items to pick up

    ![image](https://user-images.githubusercontent.com/110352438/234303782-c3edb0e9-12d3-422c-bc7e-1117088dbeb8.png)

9. Commit your changes to the branch by using: ```git commit -m "US{Number} - Describe your changes briefly"```

10. Run ```git push```
