https://portal.liferay.dev/docs/7-1/tutorials/-/knowledge_base/t/servlet-filters

1. Implement a servlet filter that will add the link to the D&M info panel
1. Implement a service that will recognize the link and redirect to the actual folder with all params..

```
<div id="_com_liferay_document_library_web_portlet_DLAdminPortlet_sidebarPanel">
    <div class="sidebar-header">
        ....

        <h1 class="sidebar-title">
            Home
        </h1>

        <h2 class="sidebar-subtitle">
            Folder
        </h2>
        
        <PUT LINK HERE>
    </div>

    <div class="sidebar-body">
    ...
</div>
```