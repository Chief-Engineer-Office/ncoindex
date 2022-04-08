## 五 工 資 訊 教 室
Five Engineer Office
<iframe src="https://calendar.google.com/calendar/embed?title=%E6%96%B0%E5%B7%A5%E8%99%95%E8%A1%8C%E4%BA%8B%E6%9B%86&amp;mode=WEEK&amp;height=600&amp;wkst=2&amp;bgcolor=%23FFFFFF&amp;src=ncotaipei.public%40gmail.com&amp;color=%23125A12&amp;src=9sbivfc8ac5sec9kao2ccnspu0%40group.calendar.google.com&amp;color=%2342104A&amp;src=ncotaipei.sec%40gmail.com&amp;color=%23B1440E&amp;src=1p0uqnhbvqrc0foihoep4h22hk%40group.calendar.google.com&amp;color=%231B887A&amp;ctz=Asia%2FTaipei" style="border-width:0" width="1024" height="768" frameborder="0" scrolling="no"></iframe>
You can use the [editor on GitHub](https://github.com/Chief-Engineer-Office/ncoindex/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Chief-Engineer-Office/ncoindex/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<div class="w3-container w3-content w3-padding-64" style="max-width:800px" id="contact">
    <h2 class="w3-wide w3-center">CONTACT</h2>
    <p class="w3-opacity w3-center"><i>Fan? Drop a note!</i></p>
    <div class="w3-row w3-padding-32">

### 主要工作區
=======

<div class="tab-content" role="main">
            <div class="searchbox-carousels-content">
                <!-- ko -->
                <homepage-searchbox params="searchClickCallback: navigateToSearch, placeholderText: searchPlaceHolder, searchHeader: searchHeader,  isSelected: isSelected" data-bind="visible: $data.currentTab() !== 'vssubs-tab' &amp;&amp; $data.isHosted">    <div class="homepage-searchbox-wrapper" role="search">
        <div class="homepage-searchbox-message">
            <h1> <span data-bind="text:$data.homePageSearchHeader()">Extensions for the Visual Studio family of products</span> </h1>
        </div>
        <div class="homepage-searchbox-container">            
            <input class="search-input" maxlength="200" data-bind="textInput: searchTerm, enable: isEnabled(), attr: { 'aria-label': placeHolder(), placeholder : placeHolder()}, hasFocus:isSelected(), event: {blur: onBlur, keydown: onKeyPress}, enterkey: submitSearchTerm" autocomplete="off" aria-label="Search Visual Studio Code extensions" placeholder="Search Visual Studio Code extensions">
            <!-- EU Cookie Consent: Consider user consent on clicking the search button by setting data-mscc-ic attribute to true -->
            <span role="button" class="searchbutton gallery-element-focus-style-moderate bowtie-icon bowtie-search" data-bind="click: submitSearchTerm, spacekey: submitSearchTerm, enterkey: submitSearchTerm, attr: {title: searchButtonTitle, 'aria-label':searchButtonTitle}, event: { focus: searchBoxFocus, blur: searchBoxBlur }" tabindex="0" data-mscc-ic="true" title="search" aria-label="search"></span>
        </div>
    </div>
</homepage-searchbox>
                <!-- /ko -->

                <div class="on-prem-page-title" data-bind="text: $data.OnPrem_Header, visible: !$data.isHosted" style="display: none;">Azure DevOps Server Extensions</div>

                <!-- ko if: $data.wasActivated()["vs-tab"] === true --><!-- /ko -->
                <!-- ko if: $data.wasActivated()["vsformac-tab"] === true --><!-- /ko -->
                <!-- ko if: $data.wasActivated()["vsts-tab"] === true --><!-- /ko -->
                <!-- ko if: $data.wasActivated()["vscode-tab"] === true -->
                <vscode-tab-content id="vscode-tab-content" role="tabpanel" params="galleryDataProvider: galleryDataProvider" data-bind="visible: $data.currentTab() === 'vscode-tab', attr: { 'aria-hidden': $data.currentTab() !== 'vscode-tab' }">    <div class="visualstudio-online-tab">
        <!-- ko if: extensionsPerCategory() -->
        <div class="category-list-container" data-bind="foreach: extensionsPerCategory()">
            <!-- ko if: !$data.isDisabled -->
                <div class="categorized-list gallery-item-cluster clearfix">
                    <h2 class="header-container" data-bind="visible: !$data.isDisabled" role="presentation">
                        <div class="section-header gallery-element-focus-style-light name" data-bind="text: $parent.getCategoryHeaderText($data.categoryName), attr: {id: $parent.getCategoriesID($index())}" role="heading" aria-level="1" id="HeaderID_vscode_Featured">Featured</div>
                        <!-- ko if: $parent.isTrendingCategoryType($data.categoryName) --><!-- /ko -->  
                        <!-- ko if: $data.hasMoreExtensions &&  $parent.showSeeMore($data.categoryName) --><!-- /ko -->
                    </h2>
                    <div class="item-list-container clearfix" data-bind="visible: !$data.isDisabled, component: {name:&quot;gallery-carousel&quot;, params: {viewModel: $parent.getCarouselViewModel($data)}}">    <div class="carousel-nav prev" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()"></div>
    <div class="carousel-wrapperHomePage">
        <ul class="carousel" data-bind="foreach: items, event: { keydown: carouselKeyHandler }, attr: {id: carouselIdSelector}, style: {width: cssStyleWidth}" id="vscode_Featured" style="width: 1173px;">
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=donjayamanne.python-environment-manager" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Python Environment Manager by publisher Don Jayamanne with install count 1M Average rating: 4.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Python Environment Manager">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="View and manage Python environments &amp; pacakges.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://donjayamanne.gallerycdn.vsassets.io/extensions/donjayamanne/python-environment-manager/1.0.3/1636510257855/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="View and manage Python environments &amp; pacakges.">Python Environment Manager</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 30px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">1M</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Don Jayamanne">Don Jayamanne</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 4.0 out of 5" title="Average rating: 4.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=Cardinal90.multi-cursor-case-preserve" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Multiple cursor case preserve by publisher Cardinal90 with install count 43.8K Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Multiple cursor case preserve">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Preserves case when editing with multiple cursors">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://cardinal90.gallerycdn.vsassets.io/extensions/cardinal90/multi-cursor-case-preserve/1.0.5/1579704717839/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Preserves case when editing with multiple cursors">Multiple cursor case preserve</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 30px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">43.8K</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Cardinal90">Cardinal90</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=sswg.swift-lang" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Swift by publisher Swift Server Work Group with install count 19.7K Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Swift">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Swift Language Support for Visual Studio Code.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://sswg.gallerycdn.vsassets.io/extensions/sswg/swift-lang/0.4.3/1649143933375/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Swift Language Support for Visual Studio Code.">Swift</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">19.7K</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Swift Server Work Group">Swift Server Work Group</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=Trunk.io" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Trunk by publisher Trunk with install count 12.9K Average rating: 4.8 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Trunk">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="The last linter you'll ever need">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://trunk.gallerycdn.vsassets.io/extensions/trunk/io/0.2.1/1643834869772/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="The last linter you'll ever need">Trunk</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">12.9K</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Trunk">Trunk</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain -->
                    <div class="core-info-third-row">
                        <i class="verified-domain-icon" data-bind="attr: { title: verifiedDomainText }, text: verifiedDomainIcon" role="presentation" title="Verified Domain"></i>
                        <div class="publisher-domain">
                            <span data-bind="text: item.publisherDomain, attr: { title: item.publisherDomain }" title="trunk.io">trunk.io</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 4.8 out of 5" title="Average rating: 4.8 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=ArianJamasb.protein-viewer" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Protein Viewer by publisher Arian Jamasb with install count 3.7K Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Protein Viewer">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Visualise 3D biological structures in the editor">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://arianjamasb.gallerycdn.vsassets.io/extensions/arianjamasb/protein-viewer/0.0.8/1643635902496/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Visualise 3D biological structures in the editor">Protein Viewer</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">3.7K</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Arian Jamasb">Arian Jamasb</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=unoplatform.vscode" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Uno Platform by publisher Uno Platform with install count 2.7K Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Uno Platform">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Uno Platform Projects XAML Completion and Hot Reload support for VS Code">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://unoplatform.gallerycdn.vsassets.io/extensions/unoplatform/vscode/0.3.2/1648134312423/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Uno Platform Projects XAML Completion and Hot Reload support for VS Code">Uno Platform</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">2.7K</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Uno Platform">Uno Platform</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain -->
                    <div class="core-info-third-row">
                        <i class="verified-domain-icon" data-bind="attr: { title: verifiedDomainText }, text: verifiedDomainIcon" role="presentation" title="Verified Domain"></i>
                        <div class="publisher-domain">
                            <span data-bind="text: item.publisherDomain, attr: { title: item.publisherDomain }" title="platform.uno">platform.uno</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        </ul>
        <!-- ko if: items().length == 0 --><!-- /ko -->
    </div>
    <div data-bind="if: !isSpinnerDisabled()"></div>
    <div class="carousel-indicators" data-bind="foreach: indicators"></div>
    <div class="carousel-nav next" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()"></div>
    <span data-bind="template: { afterRender: componentLoaded() }"></span>
</div>
                </div>
            <!-- /ko -->
        
            <!-- ko if: !$data.isDisabled -->
                <div class="categorized-list gallery-item-cluster clearfix">
                    <h2 class="header-container" data-bind="visible: !$data.isDisabled" role="presentation">
                        <div class="section-header gallery-element-focus-style-light name" data-bind="text: $parent.getCategoryHeaderText($data.categoryName), attr: {id: $parent.getCategoriesID($index())}" role="heading" aria-level="1" id="HeaderID_vscode_TrendingWeekly">Trending</div>
                        <!-- ko if: $parent.isTrendingCategoryType($data.categoryName) -->
                        <span class="drop-down" data-bind="component: {name: 'drop-down-control', params: $parent.getDropDownViewModelParams()}">    <span class="drop-down-options">
        <div role="button" aria-haspopup="true" class="trending-dropdown" data-bind="attr: {tabindex: '0', 'aria-expanded' : isExpanded}, 
             click: dropDownClick(), 
             enterkey: dropDownClick(), 
             spacekey: dropDownClick()" tabindex="0" aria-expanded="false">      
            <!-- EU Cookie Consent: Consider user consent on clicking anywhere in drop-dwon text by setting data-mscc-ic attribute to true -->
            <span data-bind="attr: {title: chosenDropDownElement().elementLabel}, text: chosenDropDownElement().elementLabel" class="dropdown-text" data-mscc-ic="true" title="this week">this week</span>
            <span class="bowtie-icon bowtie-chevron-down dropdown-icon" data-mscc-ic="true"></span>
        </div>
        <div class="dropdown-menu-container" tabindex="-1">
            <ul role="menu" class="dropdown-menu" tabindex="-1" data-bind="visible: menuVisible, foreach: dropDownElements" style="display: none;">
                <li role="menuitem" class="trending-dropdown-menu-item" tabindex="-1" data-bind="text: $data.elementLabel, event: {
                    click: $parent.optionChange($index()),
                    focus: $parent.getFocus(),
                    mouseover: $parent.mouseOver(),
                    keydown:  $parent.keyPress($index())}, attr: {'aria-expanded' : $parent.isExpanded}" aria-expanded="false">today</li>
            
                <li role="menuitem" class="trending-dropdown-menu-item" tabindex="-1" data-bind="text: $data.elementLabel, event: {
                    click: $parent.optionChange($index()),
                    focus: $parent.getFocus(),
                    mouseover: $parent.mouseOver(),
                    keydown:  $parent.keyPress($index())}, attr: {'aria-expanded' : $parent.isExpanded}" aria-expanded="false">this week</li>
            
                <li role="menuitem" class="trending-dropdown-menu-item" tabindex="-1" data-bind="text: $data.elementLabel, event: {
                    click: $parent.optionChange($index()),
                    focus: $parent.getFocus(),
                    mouseover: $parent.mouseOver(),
                    keydown:  $parent.keyPress($index())}, attr: {'aria-expanded' : $parent.isExpanded}" aria-expanded="false">this month</li>
            </ul>
        </div>
    </span>
</span>
                        <!-- /ko -->  
                        <!-- ko if: $data.hasMoreExtensions &&  $parent.showSeeMore($data.categoryName) --><!-- /ko -->
                    </h2>
                    <div class="item-list-container clearfix" data-bind="visible: !$data.isDisabled, component: {name:&quot;gallery-carousel&quot;, params: {viewModel: $parent.getCarouselViewModel($data)}}">    <div class="carousel-nav prev" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()">
        <a href="" role="button" class="carousel-prev gallery-element-focus-style-light disabled" data-bind="click: scrollLeft, spacekey: scrollLeft, attr: { title: scrollLeftTitle, tabindex: getTabIndexForLeftNavigator(), 'aria-disabled': isLeftScrollDisabled(),  'aria-label': ariaLabelForLeftScroll }, css: { disabled: isLeftScrollDisabled }" title="scroll left" tabindex="-1" aria-disabled="true" aria-label="scroll left to see more TrendingWeekly extensions">
            <i class="bowtie-icon bowtie-chevron-left"></i>
        </a>
    </div>
    <div class="carousel-wrapperHomePage">
        <ul class="carousel" data-bind="foreach: items, event: { keydown: carouselKeyHandler }, attr: {id: carouselIdSelector}, style: {width: cssStyleWidth}" id="vscode_Trending" style="width: 3519px;">
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=kaisei-kto.krnl-execute" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension KRNL Execute Extension by publisher kaisei-kto with install count 393 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="KRNL Execute Extension">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Executes the code from your Visual Studio Code's current tab">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://kaisei-kto.gallerycdn.vsassets.io/extensions/kaisei-kto/krnl-execute/0.0.2/1648882743679/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Executes the code from your Visual Studio Code's current tab">KRNL Execute Extension</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 30px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">393</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="kaisei-kto">kaisei-kto</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=lyngai.vscode-eslint-ts-fix" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension ESLint-Fix by publisher lyngai with install count 125 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="ESLint-Fix">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="This is a fork of microsoft/vscode-eslint that fixes typescript-eslint parsing errors in symlink workspaces.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://lyngai.gallerycdn.vsassets.io/extensions/lyngai/vscode-eslint-ts-fix/2.2.2/1648918467676/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="This is a fork of microsoft/vscode-eslint that fixes typescript-eslint parsing errors in symlink workspaces.">ESLint-Fix</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">125</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="lyngai">lyngai</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=tscpp.xit" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension xit! by publisher tscpp with install count 103 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="xit!">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Language support for todo lists with xit syntax.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/Header/default_icon.png">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Language support for todo lists with xit syntax.">xit!</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">103</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="tscpp">tscpp</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=piousdeer.adwaita-theme" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Adwaita by publisher piousdeer with install count 446 Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Adwaita">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Theme for the GNOME desktop">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://piousdeer.gallerycdn.vsassets.io/extensions/piousdeer/adwaita-theme/1.0.1/1649181818502/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Theme for the GNOME desktop">Adwaita</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">446</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="piousdeer">piousdeer</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=YoanBernabeu.yoandevpack" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension YoanDevPack by publisher Yoan Bernabeu with install count 217 Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="YoanDevPack">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Best Extensions for PHP/Symfony Developers">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://yoanbernabeu.gallerycdn.vsassets.io/extensions/yoanbernabeu/yoandevpack/0.0.3/1648839938169/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Best Extensions for PHP/Symfony Developers">YoanDevPack</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">217</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Yoan Bernabeu">Yoan Bernabeu</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain -->
                    <div class="core-info-third-row">
                        <i class="verified-domain-icon" data-bind="attr: { title: verifiedDomainText }, text: verifiedDomainIcon" role="presentation" title="Verified Domain"></i>
                        <div class="publisher-domain">
                            <span data-bind="text: item.publisherDomain, attr: { title: item.publisherDomain }" title="yoandev.co">yoandev.co</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=FlutterBricksProductions.SideGuide" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension SideGuide by publisher FlutterBricksProductions with install count 217 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="SideGuide">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="SideGuide is a full flutter tutorial integrated directly into your favorite editor!">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://flutterbricksproductions.gallerycdn.vsassets.io/extensions/flutterbricksproductions/sideguide/0.1.0/1649206472658/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="SideGuide is a full flutter tutorial integrated directly into your favorite editor!">SideGuide</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">217</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="FlutterBricksProductions">FlutterBricksProductions</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        </ul>
        <!-- ko if: items().length == 0 --><!-- /ko -->
    </div>
    <div data-bind="if: !isSpinnerDisabled()"></div>
    <div class="carousel-indicators" data-bind="foreach: indicators"></div>
    <div class="carousel-nav next" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()">
        <a href="" role="button" class="carousel-next gallery-element-focus-style-light" data-bind="click: scrollRight, spacekey: scrollRight, hasFocus: rightArrowFocused, attr: { title: scrollRightTitle, tabindex:  getTabIndexForRightNavigator(), 'aria-disabled': isRightScrollDisabled(), 'aria-label': ariaLabelForRightScroll }, css: { disabled: isRightScrollDisabled }" title="scroll right" tabindex="0" aria-label="scroll right to see more TrendingWeekly extensions">
            <i class="bowtie-icon bowtie-chevron-right"></i>
        </a>
    </div>
    <span data-bind="template: { afterRender: componentLoaded() }"></span>
</div>
                </div>
            <!-- /ko -->
        
            <!-- ko if: !$data.isDisabled -->
                <div class="categorized-list gallery-item-cluster clearfix">
                    <h2 class="header-container" data-bind="visible: !$data.isDisabled" role="presentation">
                        <div class="section-header gallery-element-focus-style-light name" data-bind="text: $parent.getCategoryHeaderText($data.categoryName), attr: {id: $parent.getCategoriesID($index())}" role="heading" aria-level="1" id="HeaderID_vscode_MostPopular">Most Popular</div>
                        <!-- ko if: $parent.isTrendingCategoryType($data.categoryName) --><!-- /ko -->  
                        <!-- ko if: $data.hasMoreExtensions &&  $parent.showSeeMore($data.categoryName) -->
                        <a class="see-more" data-bind="attr: {href: $data.seeMoreLink, aria-label: $parent.getSeeMoreAriaLabel($data.categoryName)},event: {keypress: $parent.getkeyPressed($index())}, click: $parent.getClicked($data.categoryName)" href="/search?sortBy=Installs&amp;category=All%20categories&amp;target=VSCode" aria-label="See more about Most Popular extensions">
                            <span data-bind="text: $parent.seeMoreString">See more</span>
                            <span class="bowtie-icon bowtie-navigate-forward-circle"></span>
                        </a>
                        <!-- /ko -->
                    </h2>
                    <div class="item-list-container clearfix" data-bind="visible: !$data.isDisabled, component: {name:&quot;gallery-carousel&quot;, params: {viewModel: $parent.getCarouselViewModel($data)}}">    <div class="carousel-nav prev" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()">
        <a href="" role="button" class="carousel-prev gallery-element-focus-style-light disabled" data-bind="click: scrollLeft, spacekey: scrollLeft, attr: { title: scrollLeftTitle, tabindex: getTabIndexForLeftNavigator(), 'aria-disabled': isLeftScrollDisabled(),  'aria-label': ariaLabelForLeftScroll }, css: { disabled: isLeftScrollDisabled }" title="scroll left" tabindex="-1" aria-disabled="true" aria-label="scroll left to see more Most Popular extensions">
            <i class="bowtie-icon bowtie-chevron-left"></i>
        </a>
    </div>
    <div class="carousel-wrapperHomePage">
        <ul class="carousel" data-bind="foreach: items, event: { keydown: carouselKeyHandler }, attr: {id: carouselIdSelector}, style: {width: cssStyleWidth}" id="vscode_MostPopular" style="width: 4692px;">
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=ms-python.python" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Python by publisher Microsoft with install count 54.1M Average rating: 4.2 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Python">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="IntelliSense (Pylance), Linting, Debugging (multi-threaded, remote), Jupyter Notebooks, code formatting, refactoring, unit tests, and more.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://ms-python.gallerycdn.vsassets.io/extensions/ms-python/python/2022.5.10981002/1649412304017/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="IntelliSense (Pylance), Linting, Debugging (multi-threaded, remote), Jupyter Notebooks, code formatting, refactoring, unit tests, and more.">Python</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">54.1M</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Microsoft">Microsoft</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain -->
                    <div class="core-info-third-row">
                        <i class="verified-domain-icon" data-bind="attr: { title: verifiedDomainText }, text: verifiedDomainIcon" role="presentation" title="Verified Domain"></i>
                        <div class="publisher-domain">
                            <span data-bind="text: item.publisherDomain, attr: { title: item.publisherDomain }" title="microsoft.com">microsoft.com</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 4.2 out of 5" title="Average rating: 4.2 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=ms-toolsai.jupyter" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Jupyter by publisher Microsoft with install count 34.6M Average rating: 2.6 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Jupyter">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Jupyter notebook support, interactive programming and computing that supports Intellisense, debugging and more.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://ms-toolsai.gallerycdn.vsassets.io/extensions/ms-toolsai/jupyter/2022.4.1001001004/1649408875988/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Jupyter notebook support, interactive programming and computing that supports Intellisense, debugging and more.">Jupyter</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">34.6M</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Microsoft">Microsoft</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain -->
                    <div class="core-info-third-row">
                        <i class="verified-domain-icon" data-bind="attr: { title: verifiedDomainText }, text: verifiedDomainIcon" role="presentation" title="Verified Domain"></i>
                        <div class="publisher-domain">
                            <span data-bind="text: item.publisherDomain, attr: { title: item.publisherDomain }" title="microsoft.com">microsoft.com</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 2.6 out of 5" title="Average rating: 2.6 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent -->
        <img alt="" class="star half-star" data-bind="attr:{src: halfStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/HalfStar.svg">
        <!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=ms-vscode.cpptools" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension C/C++ by publisher Microsoft with install count 30M Average rating: 3.5 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="C/C++">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="C/C++ IntelliSense, debugging, and code browsing.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/cpptools/1.9.7/1648071434432/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="C/C++ IntelliSense, debugging, and code browsing.">C/C++</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">30M</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Microsoft">Microsoft</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain -->
                    <div class="core-info-third-row">
                        <i class="verified-domain-icon" data-bind="attr: { title: verifiedDomainText }, text: verifiedDomainIcon" role="presentation" title="Verified Domain"></i>
                        <div class="publisher-domain">
                            <span data-bind="text: item.publisherDomain, attr: { title: item.publisherDomain }" title="microsoft.com">microsoft.com</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 3.5 out of 5" title="Average rating: 3.5 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent -->
        <img alt="" class="star half-star" data-bind="attr:{src: halfStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/HalfStar.svg">
        <!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=ms-python.vscode-pylance" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Pylance by publisher Microsoft with install count 27.4M Average rating: 3.4 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Pylance">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="A performant, feature-rich language server for Python in VS Code">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://ms-python.gallerycdn.vsassets.io/extensions/ms-python/vscode-pylance/2022.4.0/1649288263385/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="A performant, feature-rich language server for Python in VS Code">Pylance</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">27.4M</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Microsoft">Microsoft</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain -->
                    <div class="core-info-third-row">
                        <i class="verified-domain-icon" data-bind="attr: { title: verifiedDomainText }, text: verifiedDomainIcon" role="presentation" title="Verified Domain"></i>
                        <div class="publisher-domain">
                            <span data-bind="text: item.publisherDomain, attr: { title: item.publisherDomain }" title="microsoft.com">microsoft.com</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 3.4 out of 5" title="Average rating: 3.4 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent -->
        <img alt="" class="star half-star" data-bind="attr:{src: halfStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/HalfStar.svg">
        <!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=ritwickdey.LiveServer" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Live Server by publisher Ritwick Dey with install count 20.4M Average rating: 4.4 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Live Server">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Launch a development local Server with live reload feature for static &amp; dynamic pages">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://ritwickdey.gallerycdn.vsassets.io/extensions/ritwickdey/liveserver/5.7.5/1646738284779/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Launch a development local Server with live reload feature for static &amp; dynamic pages">Live Server</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">20.4M</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Ritwick Dey">Ritwick Dey</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 4.4 out of 5" title="Average rating: 4.4 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent -->
        <img alt="" class="star half-star" data-bind="attr:{src: halfStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/HalfStar.svg">
        <!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=esbenp.prettier-vscode" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Prettier - Code formatter by publisher Prettier with install count 20.1M Average rating: 3.7 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Prettier - Code formatter">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Code formatter using prettier">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://esbenp.gallerycdn.vsassets.io/extensions/esbenp/prettier-vscode/9.5.0/1648513363698/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Code formatter using prettier">Prettier - Code formatter</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 30px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">20.1M</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Prettier">Prettier</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 3.7 out of 5" title="Average rating: 3.7 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent -->
        <img alt="" class="star half-star" data-bind="attr:{src: halfStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/HalfStar.svg">
        <!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        </ul>
        <!-- ko if: items().length == 0 --><!-- /ko -->
    </div>
    <div data-bind="if: !isSpinnerDisabled()"></div>
    <div class="carousel-indicators" data-bind="foreach: indicators"></div>
    <div class="carousel-nav next" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()">
        <a href="" role="button" class="carousel-next gallery-element-focus-style-light" data-bind="click: scrollRight, spacekey: scrollRight, hasFocus: rightArrowFocused, attr: { title: scrollRightTitle, tabindex:  getTabIndexForRightNavigator(), 'aria-disabled': isRightScrollDisabled(), 'aria-label': ariaLabelForRightScroll }, css: { disabled: isRightScrollDisabled }" title="scroll right" tabindex="0" aria-label="scroll right to see more Most Popular extensions">
            <i class="bowtie-icon bowtie-chevron-right"></i>
        </a>
    </div>
    <span data-bind="template: { afterRender: componentLoaded() }"></span>
</div>
                </div>
            <!-- /ko -->
        
            <!-- ko if: !$data.isDisabled --><!-- /ko -->
        
            <!-- ko if: !$data.isDisabled --><!-- /ko -->
        
            <!-- ko if: !$data.isDisabled -->
                <div class="categorized-list gallery-item-cluster clearfix">
                    <h2 class="header-container" data-bind="visible: !$data.isDisabled" role="presentation">
                        <div class="section-header gallery-element-focus-style-light name" data-bind="text: $parent.getCategoryHeaderText($data.categoryName), attr: {id: $parent.getCategoriesID($index())}" role="heading" aria-level="1" id="HeaderID_vscode_RecentlyAdded">Recently Added</div>
                        <!-- ko if: $parent.isTrendingCategoryType($data.categoryName) --><!-- /ko -->  
                        <!-- ko if: $data.hasMoreExtensions &&  $parent.showSeeMore($data.categoryName) -->
                        <a class="see-more" data-bind="attr: {href: $data.seeMoreLink, aria-label: $parent.getSeeMoreAriaLabel($data.categoryName)},event: {keypress: $parent.getkeyPressed($index())}, click: $parent.getClicked($data.categoryName)" href="/search?sortBy=PublishedDate&amp;category=All%20categories&amp;target=VSCode" aria-label="See more about Recently Added extensions">
                            <span data-bind="text: $parent.seeMoreString">See more</span>
                            <span class="bowtie-icon bowtie-navigate-forward-circle"></span>
                        </a>
                        <!-- /ko -->
                    </h2>
                    <div class="item-list-container clearfix" data-bind="visible: !$data.isDisabled, component: {name:&quot;gallery-carousel&quot;, params: {viewModel: $parent.getCarouselViewModel($data)}}">    <div class="carousel-nav prev" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()">
        <a href="" role="button" class="carousel-prev gallery-element-focus-style-light disabled" data-bind="click: scrollLeft, spacekey: scrollLeft, attr: { title: scrollLeftTitle, tabindex: getTabIndexForLeftNavigator(), 'aria-disabled': isLeftScrollDisabled(),  'aria-label': ariaLabelForLeftScroll }, css: { disabled: isLeftScrollDisabled }" title="scroll left" tabindex="-1" aria-disabled="true" aria-label="scroll left to see more Recently Added extensions">
            <i class="bowtie-icon bowtie-chevron-left"></i>
        </a>
    </div>
    <div class="carousel-wrapperHomePage">
        <ul class="carousel" data-bind="foreach: items, event: { keydown: carouselKeyHandler }, attr: {id: carouselIdSelector}, style: {width: cssStyleWidth}" id="vscode_RecentlyAdded" style="width: 3519px;">
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=subito.vedere-bla-bla-baby-altahd" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Bla Bla Baby Streaming (2022) Gratis in Ita HD by publisher subito with install count 0 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Bla Bla Baby Streaming (2022) Gratis in Ita HD">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="dove guardare gratuito ita">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://subito.gallerycdn.vsassets.io/extensions/subito/vedere-bla-bla-baby-altahd/0.2.1/1649429068748/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="dove guardare gratuito ita">Bla Bla Baby Streaming (2022) Gratis in Ita HD</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 30px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'" style="display: none;">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">0</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="subito">subito</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=keisin0.hk-kebeletkaler" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension 劇場版 咒術迴戰 0電影在線-年电影2022-觀看完整版 by publisher keisin0 with install count 0 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="劇場版 咒術迴戰 0電影在線-年电影2022-觀看完整版">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/Header/default_icon.png">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}">劇場版 咒術迴戰 0電影在線-年电影2022-觀看完整版</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 30px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'" style="display: none;">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">0</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="keisin0">keisin0</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=Maikcyphlock.half-life-theme" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Half Life theme by publisher Maikcyphlock with install count 3 Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Half Life theme">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Theme inspired in Half Life, was one of the first games that I've played.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://maikcyphlock.gallerycdn.vsassets.io/extensions/maikcyphlock/half-life-theme/0.0.3/1649428551326/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Theme inspired in Half Life, was one of the first games that I've played.">Half Life theme</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">3</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Maikcyphlock">Maikcyphlock</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=milepanic.daisy-light-theme" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Daisy Theme by publisher Mile Panic with install count 1 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Daisy Theme">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Light color theme">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/Header/default_icon.png">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Light color theme">Daisy Theme</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">1</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Mile Panic">Mile Panic</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=oas2tree.oas-2-tree" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension OAS-2-Tree by publisher oas2tree with install count 0 Average rating: 0.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="OAS-2-Tree">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="OpenAPI Specification text to tree transformation visualizer.">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://oas2tree.gallerycdn.vsassets.io/extensions/oas2tree/oas-2-tree/0.0.1/1649419739786/Microsoft.VisualStudio.Services.Icons.Small">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="OpenAPI Specification text to tree transformation visualizer.">OAS-2-Tree</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 0px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'" style="display: none;">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">0</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="oas2tree">oas2tree</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 0.0 out of 5" title="Average rating: 0.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() --><!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() -->
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        
        <img alt="" class="star empty-star" data-bind="attr:{src: $parent.emptyStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/EmptyStar.svg">
        <!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() -->
            <li class="carousel-item" role="listitem" data-bind="component: {name: $parent.componentName, params: {item: $data, containerName: $parent.carouselIdSelector, removeTabFocus: $index() < $parent._viewPortStartIndex() || $index() >= $parent._viewPortStartIndex() + $parent._numberOfItemsToDisplay}}">    <a class="gallery-item-card-container" data-bind="attr: { href: item.link, target: linkTarget, tabindex : getTabIndex, 'aria-label': getScreenReaderText() }, click: clickItem()" href="/items?itemName=mdmarufsarker.maruf-sarker" tabindex="function(){return this.removeTabFocus?&quot;-1&quot;:&quot;0&quot;}" aria-label="Extension Maruf Sarker VSCode Dark Theme by publisher Md. Maruf Sarker with install count 4 Average rating: 5.0 out of 5 and is of FREE category.">
        <div class="gallery-item-cardHomePage" data-bind="attr: { title: item.title}" title="Maruf Sarker VSCode Dark Theme">
            <div class="cover">
                <!-- ko if: showCertifiedBadge --><!-- /ko -->
                <div class="icon-cell" data-bind="template: { name: 'image-template', data: imageViewModel}, attr: { title: item.summary }" title="Maruf Sarker VSCode Dark Theme">
    <img class="image-display item-icon" alt="" data-bind="attr: { src: imageSrc}, css: imageStyle, visible: imageVisible" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/Header/default_icon.png">
    <div class="bowtie-icon" data-bind="visible: (!imageVisible &amp;&amp; !bowtieStyle), css: bowtieStyle " style="display: none;"></div>
    <span data-bind="template: { afterRender: componentLoaded($element) }"></span>
</div>
                <div class="core-info-cell">
                    <div class="name">
                        <span class="item-title" data-bind="text: item.title, attr: { title: item.summary}" title="Maruf Sarker VSCode Dark Theme">Maruf Sarker VSCode Dark Theme</span>
                        <span class="text-fadeout" data-bind="style: {width: calculateWidthBasedOnSibling($element, 'item-title', 158, '30px')}" style="width: 30px;"></span>
                    </div>
                    <!--ko ifnot: showInstallCount --><!-- /ko -->
                    <!--ko if: showInstallCount -->
                    <div class="core-info-second-row">
                        <span class="installs" data-bind="visible: item.installCount &amp;&amp; item.installCount !== '0'">
                            <i class="bowtie-icon bowtie-install install-icon"></i>
                            <span class="install-count" data-bind="text: item.installCount">4</span>
                        </span>
                        <div class="publisher">
                            <span data-bind="text: item.author , attr: { title: item.author }" title="Md. Maruf Sarker">Md. Maruf Sarker</span>
                            <span class="text-fadeout"></span>
                        </div>
                    </div>
                    <!-- /ko -->
                    <!--ko if: showDomain --><!-- /ko -->
                </div>
            </div>
            <div class="stats-and-offer">
                <!-- ko if: showRatingReview -->
                <div class="rating-and-price">                    
                    <div role="img" class="rating" data-bind="component: {name: 'gallery-rating-control', params: ratingControlParams}, attr: { 'alt': averageRatingText, title: averageRatingText }" alt="Average rating: 5.0 out of 5" title="Average rating: 5.0 out of 5">    <div class="rating-control">
        <!-- ko foreach: fullStarArray() -->
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        
        <img alt="" class="star full-star" data-bind="attr:{src: $parent.fullStarPath}" src="https://cdn.vsassets.io/v/M200_20220322.2/_content/FullStar.svg">
        <!-- /ko -->
        <!-- ko if: halfStarPresent --><!-- /ko -->
        <!-- ko foreach: emptyStarArray() --><!-- /ko -->
    </div>
</div>                    
                    <div class="pricing-tag" data-bind="text: item.costCategory, attr: { title: item.costCategory }" title="FREE">FREE</div>
                    <span class="text-fadeout"></span>
                </div>
                <!-- /ko -->
                <!-- ko ifnot: showRatingReview --><!-- /ko -->
            </div>                
        </div>
    </a>
</li>
            <!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        
            <!-- ko if: $index() < $parent.numberOfItemsToRender() --><!-- /ko -->
        </ul>
        <!-- ko if: items().length == 0 --><!-- /ko -->
    </div>
    <div data-bind="if: !isSpinnerDisabled()"></div>
    <div class="carousel-indicators" data-bind="foreach: indicators"></div>
    <div class="carousel-nav next" data-bind="if: !isLeftScrollDisabled() || !isRightScrollDisabled() || isfetching()">
        <a href="" role="button" class="carousel-next gallery-element-focus-style-light" data-bind="click: scrollRight, spacekey: scrollRight, hasFocus: rightArrowFocused, attr: { title: scrollRightTitle, tabindex:  getTabIndexForRightNavigator(), 'aria-disabled': isRightScrollDisabled(), 'aria-label': ariaLabelForRightScroll }, css: { disabled: isRightScrollDisabled }" title="scroll right" tabindex="0" aria-label="scroll right to see more Recently Added extensions">
            <i class="bowtie-icon bowtie-chevron-right"></i>
        </a>
    </div>
    <span data-bind="template: { afterRender: componentLoaded() }"></span>
</div>
                </div>
            <!-- /ko -->
        </div>
        <!-- /ko -->
        <i class="big-spinner bowtie-icon bowtie-spinner centered" data-bind="visible: _koShowSpinner, attr: {id: _spinnerID}" id="OtherLoadSpinner" style="display: none;"></i>
        <!-- ko if: showCategories() -->
        <div class="gallery-item-cluster categories clearfix">
            <h2 class="header-container">
                <div class="section-header gallery-element-focus-style-light name" data-bind="text: $data.categoriesString, click: $parent.getClicked($data.categoryName)">Filter by category / collection</div>
            </h2>
            <div class="tools-category item-list-container" data-bind="component: {name:&quot;gallery-item-grid&quot;, params: $data.getCategoriesViewModelParams()}">    <div class="item-grid-container" data-bind="foreach: itemArray">
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Azure&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Azure">Azure</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Data%20Science&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Data Science">Data Science</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Debuggers&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Debuggers">Debuggers</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Education&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Education">Education</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Extension%20Packs&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Extension Packs">Extension Packs</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Formatters&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Formatters">Formatters</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Keymaps&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Keymaps">Keymaps</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Language%20Packs&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Language Packs">Language Packs</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Linters&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Linters">Linters</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Machine%20Learning&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Machine Learning">Machine Learning</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Notebooks&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Notebooks">Notebooks</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Programming%20Languages&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Programming Languages">Programming Languages</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=SCM%20Providers&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="SCM Providers">SCM Providers</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Snippets&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Snippets">Snippets</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Testing&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Testing">Testing</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Themes&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Themes">Themes</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Visualization&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Visualization">Visualization</span>
            </div>
        </a>
    </div>
</div>
    
        <div class="grid-item" data-bind="component: {name: $parent.componentName, params: {item: $data}}">    <div class="category-entry">
        <a data-bind="attr: { href: link, target: linkTarget },  click: clickTile()" href="/search?sortBy=Installs&amp;category=Other&amp;target=VSCode">
            <div class="main-cell">
                <span class="name" data-bind="text: name, attr: { title: name }" title="Other">Other</span>
            </div>
        </a>
    </div>
</div>
    </div>
</div>
        </div>
        <!-- /ko -->
        <!-- ko if: !isHosted() --><!-- /ko -->    
        <div data-bind="if: hasError"></div>
    </div>
</vscode-tab-content>
                <!-- /ko -->
                <!-- ko if: $data.wasActivated()["vssubs-tab"] === true --><!-- /ko -->
            </div>
        </div>