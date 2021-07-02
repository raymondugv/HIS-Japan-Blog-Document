Administrator Document
---

- [How to login](#how-to-login)
- [User Information](#user-information)
  - [User](#user)
    - [Create new User](#create-new-user)
    - [Edit User](#edit-user)
    - [Delete User](#delete-user)
  - [Role](#role)
- [Content Management](#content-management)
  - [Posts](#posts)
  - [Categories](#categories)
    - [Create new Category](#create-new-category)
    - [Edit Category](#edit-category)
    - [Delete Category](#delete-category)
  - [Famous Theme](#famous-theme)
    - [Add new Famous Theme](#add-new-famous-theme)
    - [Edit Famous Theme](#edit-famous-theme)
    - [Delete Famous Theme](#delete-famous-theme)
  - [Special Features](#special-features)
    - [Add new Special Feature](#add-new-special-feature)
    - [Edit Special Feature](#edit-special-feature)
    - [Delete Special Feature](#delete-special-feature)
  - [Popular Search](#popular-search)
    - [Create new Popular Search](#create-new-popular-search)
    - [Edit Popular Search](#edit-popular-search)
    - [Delete Popular Search](#delete-popular-search)
  - [Advertising](#advertising)
    - [Create new Advertising Banner](#create-new-advertising-banner)
    - [Edit Advertising Banner](#edit-advertising-banner)
    - [Delete Advertising Banner](#delete-advertising-banner)
- [Administrator Tools](#administrator-tools)
  - [Countries](#countries)
  - [Site Setting](#site-setting)

# How to login
Please check this [link](https://github.com/raymondugv/HIS-Japan-Blog-Document#how-to-login)

# User Information
To control User and Role of the system
## User

![image](https://user-images.githubusercontent.com/21214764/124234256-fe3f9580-db3d-11eb-90fd-1b2590f50014.png)

### Create new User
1. Click on `CREATE NEW USER` button

![image](https://user-images.githubusercontent.com/21214764/124234313-11526580-db3e-11eb-8473-19be43bbc5e5.png)

2. Fill user information
   
   More detail, check [this page](https://github.com/raymondugv/HIS-Japan-Blog-Document#change-user-information)
3. Save

### Edit User
Check [this page](https://github.com/raymondugv/HIS-Japan-Blog-Document#change-user-information)
### Delete User
1. Select on `Trash` icon at the end of the user row that you want to delete.

![image](https://user-images.githubusercontent.com/21214764/124234462-419a0400-db3e-11eb-9898-94479af49da9.png)

2. Confirm delete chosen user on showing modal

![image](https://user-images.githubusercontent.com/21214764/124234530-57a7c480-db3e-11eb-9396-6a9506b2142a.png)

3. Page reloaded and check if user account deleted.


## Role
View Role setting. Currently, only `Super Admin` can only change this setting.

![image](https://user-images.githubusercontent.com/21214764/124234713-9473bb80-db3e-11eb-8484-2959afa7a1b6.png)

This would be updated soon.
# Content Management

## Posts
Please check [this page](https://github.com/raymondugv/HIS-Japan-Blog-Document#posts) for more information

## Categories

![image](https://user-images.githubusercontent.com/21214764/124234752-a3f30480-db3e-11eb-8a84-2710828d93b1.png)

### Create new Category
1. Click on `CREATE NEW` button on top right of the page

![image](https://user-images.githubusercontent.com/21214764/124234772-abb2a900-db3e-11eb-9ce1-17198d3a683b.png)

2. Fill the page with category information, in which:

 ![image](https://user-images.githubusercontent.com/21214764/124234973-ea486380-db3e-11eb-8f2b-f02e4086e4fe.png)
  
| Field | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Category Name in English` | `text` | **Required**. Category name, but in English |
| `Slug` | `url` | **Required** Usually this will be generated after you type Category Name in English. This is the URL of this category page. This must be **unique** |
| `Parent Category` | `select` | Parent Category of this Category |
| `Description` | `text` | **Required** English description of this Category |
| `Icon` | `image` | Icon for this Category (will not globally showed) |
| `Image` | `image` | **Required** Image of this Category |
| `Secondary Image` | `image` | This showing the map of this area (used for Category which has parent is `Destination` only) |
| `Category name in {language}` | `text` | **Required** Category translation from English to {language} of this Category |
| `Category description in {lang}` | `text` | **Required** Translated to {lang} of this category description |

3. Save & Update


### Edit Category
1. Click on `pencil` icon at the end of the category row.

![image](https://user-images.githubusercontent.com/21214764/124235109-12d05d80-db3f-11eb-812f-5c7c85c4668b.png)

2. Change or edit Category information.
3. Save & Update
### Delete Category
1. Click on `trash` icon at the end of the category row.

![image](https://user-images.githubusercontent.com/21214764/124235223-2da2d200-db3f-11eb-88ed-23cdb43b806d.png)

2. Confirm on the showing modal.
3. The page will reload, then check user check if Category deleted.


## Famous Theme

![image](https://user-images.githubusercontent.com/21214764/124235308-46ab8300-db3f-11eb-9a45-4bff2ae4a529.png)

### Add new Famous Theme
1. Click on `CREATE NEW` button on top right of the page.

![image](https://user-images.githubusercontent.com/21214764/124235939-16181900-db40-11eb-98af-463403a60338.png)

2. Fill the page with Famous Theme information, in which

![image](https://user-images.githubusercontent.com/21214764/124235974-203a1780-db40-11eb-9564-447d4cbec931.png)

| Field | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Name` | `text` | **Required**. Name of this Famous Theme in English |
| `Short Description` | `text` | **Required**. English version of this Famous Theme's description |
| `Name in {lang}` | `text` | **Required**. {Lang} version of this Famous Theme's name |
| `Short Description in {lang}` | `text` | **Required**. {Lang} translationi of Famous Theme's short description |
| `Image` | `image` | **Required**. Image of this Famous Theme |

3. Click `Create` button so save.
### Edit Famous Theme
1. Click on `pencil` icon of selected Famous Theme.

![image](https://user-images.githubusercontent.com/21214764/124236032-2f20ca00-db40-11eb-83da-505f504f78ff.png)

2. Edit Famous Theme with new information.
3. `Save & Update`
### Delete Famous Theme
1. Click on `trash` icon of selected Famous Theme.

![image](https://user-images.githubusercontent.com/21214764/124236072-3c3db900-db40-11eb-963f-159b5e7ca5be.png)

2. Confirm on showing modal.
3. Check if selected Famous Theme deleted or not.


## Special Features

![image](https://user-images.githubusercontent.com/21214764/124236135-4eb7f280-db40-11eb-938e-c14bb943df05.png)

### Add new Special Feature
1. Click `CREATE NEW` button.

![image](https://user-images.githubusercontent.com/21214764/124236176-59728780-db40-11eb-8eb0-1b6857c649e5.png)

2. Fill all the required field

![image](https://user-images.githubusercontent.com/21214764/124236250-6c855780-db40-11eb-8a6f-6699af41f1fe.png)

| Field | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Link` | `url` | **Required**. URL of this Special Feature |
| `Image` | `image` | **Required**. Image of this Special Feature |

3. Save
### Edit Special Feature
1. Click on `pencil` icon of selected Special Feature.

![image](https://user-images.githubusercontent.com/21214764/124236298-7a3add00-db40-11eb-90a8-7b7e6ee17787.png)

2. Update information.
3. Save.
### Delete Special Feature
1. Click on `trash` icon of selected Special Feature.

![image](https://user-images.githubusercontent.com/21214764/124236324-832bae80-db40-11eb-97db-e0d28787beb7.png)

2. Confirm delete on showing modal.
3. Check if selected Special Feature deleted.

## Popular Search

![image](https://user-images.githubusercontent.com/21214764/124236375-93438e00-db40-11eb-8047-be98b7b8bf22.png)

### Create new Popular Search
1. Fill all the required field

![image](https://user-images.githubusercontent.com/21214764/124236397-99396f00-db40-11eb-9476-c22158cf70b1.png)

| Field | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Name` | `text` | **Required**. Name of this Keyword |
| `Keyword` | `text` | **Required**. Normally, this will be generated at the time Name is inputted. |

2. Save.
3. Check if created keyword showing on the list.

### Edit Popular Search
1. Click on `pencil` icon of selected keyword.

![image](https://user-images.githubusercontent.com/21214764/124236484-ae160280-db40-11eb-9d81-e64be0a2356a.png)

2. Update information.
3. Save.
4. Check if it's updated.

### Delete Popular Search
1. Click on `trash` icon of selected keyword.

![image](https://user-images.githubusercontent.com/21214764/124236543-bb32f180-db40-11eb-934a-7800b1ce9a94.png)

2. Confirm on showing modal.
3. Check if keyword deleted.


## Advertising

![image](https://user-images.githubusercontent.com/21214764/124236669-e289be80-db40-11eb-9ac4-038cef419117.png)

### Create new Advertising Banner
1. Click `CREATE NEW` button

![image](https://user-images.githubusercontent.com/21214764/124236716-f0d7da80-db40-11eb-90ef-5a187ccbfdf6.png)

2. Fill all the required field

![image](https://user-images.githubusercontent.com/21214764/124236744-f7fee880-db40-11eb-8a34-41f006c68374.png)

| Field | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Title` | `text` | **Required**. Title of this Advertisement |
| `Link` | `url` | **Required**. URL of this Advertisement |
| `Image` | `Image` | **Required**. Image of this advertisement |

3. Save.

### Edit Advertising Banner
1. Click on `pencil` icon.

![image](https://user-images.githubusercontent.com/21214764/124236787-064d0480-db41-11eb-925d-4f063b75c5ef.png)

2. Update information.
3. Save.

### Delete Advertising Banner
1. Click on `trash` icon.

![image](https://user-images.githubusercontent.com/21214764/124236818-1238c680-db41-11eb-9b6b-b219db417764.png)

2. Confirm delete on showing modal.

![image](https://user-images.githubusercontent.com/21214764/124236861-1c5ac500-db41-11eb-8e98-b60f5b2312a2.png)

3. Check if Advertisement is deleted.
# Administrator Tools

## Countries
List of Supported language on the site, if need change or create new one, please contact `Super Admin`.

![image](https://user-images.githubusercontent.com/21214764/124236936-3399b280-db41-11eb-8851-27504e875d73.png)

## Site Setting

![image](https://user-images.githubusercontent.com/21214764/124237803-229d7100-db42-11eb-9bc0-088e21f95d61.png)

| Field | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Site's Title in {lang}` | `text` | **Required**. Title of the Site in {lang} |
| `Site Description in {lang}` | `text` | **Required**. Description of the site in {lang} |
| `Site's Logo` | `image` | **Required**. Logo of the whole website |
| `Site's Favicon` | `image` | **Required**. The site's favicon, which show on Browser's tab. |
| `OpenGraph Image` | `image` | **Required**. The image which will show when homepage is pated in SNS platform. |
