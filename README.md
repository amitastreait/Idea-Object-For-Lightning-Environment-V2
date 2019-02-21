# Idea Object For Lightning Environment V2.0

### Idea Object for Salesforce Lightning Environment

Hi All, hope you are doing great and enjoying salesforce. Here in this post, I will post the Idea Object for Lightning Environment that is completely developed by using custom Lighting Component. I found that Idea Object is not available for Lightning Environment and many customers are using the idea Object they are not able to use the same if they are working with Lighting. If they wanted to use then they need to switch back to classic. It is still an [Idea](https://success.salesforce.com/ideaView?id=0873A000000E4e0QAC). So, I decided to develop the custom idea object which will help many people and also clear the concept of Lighting Development.

As I already developed the component with the required functionality so I will explain which component is responsible for which functionality. So that any developer can change as per their requirement.

Below is the list of Component used in the Idea Object for Lighting with their description: -

`1 - IdeaComponent: -` The heart of the Idea Object which is responsible for showing all the Ideas in a single page and User can also post the new Idea from this component as well. This is the alternative to Idea Tab of Salesforce Classic.
![](https://github.com/amitastreait/Idea-Object-For-Lightning-Environment-V2.0/blob/master/Idea%20Component.png)

`2 - ViewIdea.component: -` Second important component is "ViewIdea" which is responsible for showing the Idea details with the comment that have been made for that Idea. Using this component user can Edit the Idea, Post Comment, Edit and Delete the Comment.
![](https://github.com/amitastreait/Idea-Object-For-Lightning-Environment-V2.0/blob/master/View%20Idea.PNG)

`3 - CreateIdea.component: -` Another component which is responsible for creating the Idea.
![](https://github.com/amitastreait/Idea-Object-For-Lightning-Environment-V2.0/blob/master/Create%20Ideas.PNG)

`4 - EditIdea.component: -` Component responsible for Editing and deleting the existing Idea.
![](https://github.com/amitastreait/Idea-Object-For-Lightning-Environment-V2.0/blob/master/Edit%20Idea.PNG)

`5 - EditIdeaComment.component : -` The component which responsible updating the comment related to an Idea and deleting the existing the comment.

You can install the unmanaged package from.
<a href="https://githubsfdeploy.herokuapp.com/?owner=amitastreait&repo=Idea-Object-For-Lightning-Environment-V2.0">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

After you have successfully installed the Component. Give the Access to Idea Tab to the relevent Profiles and Also give the Ideas Object Permission then you are good to go.

Thanks,
Amit Singh
