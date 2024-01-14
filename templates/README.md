## Hi there 👋

Now that you are here, let me grab your coat, take the load off and put up your feet.  We are all here for code.

- 🔭 Check out [https://SergeiGolos.github.io/](https://SergeiGolos.github.io/) for my professional CV.
- 🤔 My ramblings about software can be found here: [https://bitcobblers.com](bitcobblers.com).
- 💬 Ask me about [ZeUnit](https://github.com/bitcobblers/ZeUnit) the prototype functional unit testing framework.
- 📫 How to reach me: [serge@bitcobblers.com](mailto:serge@bitcobblers.com)

## Technologies

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)


## Professional History
| Company | Position | Start Date | End Date | Tags |
| :---:   | :---: | :---: | :---: | :---: |<%for (var i = 0; i < work.length; i++) {    %>
<%var job = work[i] 
  , tags = (job.tags|| []).map(function(t) { return "`" + t + "`"}).join(", ")
%>| <%= job.company %> | <%= job.position %> | <%= job.startDate %> | <%= job.endDate %> | <%= tags %> |<%}-%>
