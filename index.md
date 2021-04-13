## Azure Machine Learning
Azure is a cloud-based platform, services offerings include data storage services, compute, networking and application services. Machine learning resources can be easily built up in Azure so that data engagers easily come to use this platform. In this part, try to show how to start up machine learning in Microsoft Azure.

## 1.Azure ML Workspace
If you do not already subscribe Azure, you should sign up for that. After subscription, sign into the Azure portal. The interface should be like this:

![image](https://user-images.githubusercontent.com/71245576/114557434-aa589b00-9c37-11eb-9dda-e7282a2ada29.png)

Create a machine learning resource, if you cannot find the machine learning resource, you can use the search engine in the marketplace, just type in machine learning and it will provide the most appropriate one. 

![image](https://user-images.githubusercontent.com/71245576/114557803-09b6ab00-9c38-11eb-95e7-a4de8c946f9f.png)

There are several configurations that are in demand of setting, subscription is a logical container used to provision resources in Azure, in which the resources put together and will bill together. 

If you do not have a related previous resource group, just create a new one. Workspace name, region, storage account, key vault and so on could be very personalized. 

![image](https://user-images.githubusercontent.com/71245576/114560179-6fa43200-9c3a-11eb-963d-94850f84b344.png)

There are other settings that may be not clear for beginers in Azure ML, do not worry about it and move it on. If you are curious about it, there is a Azure Essential Learning Course by David Elfassy helps you: https://www.linkedin.com/learning/azure-administration-essential-training

Wait for your workspace resource to be created, it configures very quickly as I see, then go to it in the portal, you can overview it in the overview page and reset it if necessary. The next step is to launch Azure Machine Learning studio. Click to launch on bottom center.

![image](https://user-images.githubusercontent.com/71245576/114566225-0d4e3000-9c40-11eb-9ead-9480a8acd4ee.png)

Three parts include within Azure ML studio: Author, Assets and Manage.

![image](https://user-images.githubusercontent.com/71245576/114563663-9adc5080-9c3d-11eb-95b9-53200b755e70.png)

## 2. Compute Instance

Compute instance is a fully managed cloud-based workstation for data scientists, it makes it easy to machine learning. To begin with, under the manage part, create a compute instance.

There are two procedures that you need to finish, choosing a virtual machine versus setting. For beginers, you can try to use the cheaper VM for just practice, feel free to choose CPU as machine type, choose the smaller size. 

![image](https://user-images.githubusercontent.com/71245576/114564520-61581500-9c3e-11eb-9a43-4caa8fcd4359.png)

In the setting step, overview the configure settings and type in a compute name as you go. The progression to create a compute instance could spend you a few minutes. 

![image](https://user-images.githubusercontent.com/71245576/114565062-ee02d300-9c3e-11eb-9de8-13e28174d630.png)

Till now, all of prerequisite matters are on shelf. The next step I will tell you how to clone some repositories from GitHub. Sometimes we need to use the file systems or something from other infrastructures. 

## 3. Clone Files from GitHub

Actually Azure provides many services to migrate resources from any infrastructures as you use. Microsoft has the tutorial to help data scientists be familiar with their services in Azure, there are some files to practice in GitHub. We so try to upload some files now. 

In Azure Machine Learning studio, choose the running compute instance, use the Jupyter link to open Jupyter Notebooks in a new browser.

![image](https://user-images.githubusercontent.com/71245576/114569175-beee6080-9c42-11eb-9b16-b2da770a697d.png)

In the Jupyter page, on the New menu, select Terminal and it will open a new tab with a shell. In this shell, change the current directory to the Users directory(cd Users), and clone the ml-basics repository from https://github.com/microsoftdocs/ml-basics. The code is:

cd Users
git clone https://github.com/microsoftdocs/ml-basics

![image](https://user-images.githubusercontent.com/71245576/114569625-24dae800-9c43-11eb-885a-57355fe914ff.png)

After the commands have completed and the checkout of the files is done, close the terminal tab and view the home page in Jupyter notebook file system. Open the Users folder it should contain an ml-basics folder, containing the files that we are going to use in the rest of excersices. 

![image](https://user-images.githubusercontent.com/71245576/114569964-6cfa0a80-9c43-11eb-9b78-33c2401c22c1.png)


## 4. Conclusion

Hitherto we successfully have accomplished a complete process to build up a platform for machine learning in Azure. We can program based on any programming languages in this compute instance. The next article I will show some EDA programming assignments in Azure, the language is Python and packages that will be used are NumPy, Pandas and Matplotlib.  







