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
    - [Create new Country Setting](#create-new-country-setting)
  - [Site Setting](#site-setting)

# How to login
Please check this [link](https://github.com/raymondugv/HIS-Japan-Blog-Document#how-to-login)

# User Information
To control User and Role of the system
## User

### Create new User
1. Click on `CREATE NEW USER` button
2. Fill user information
   
   More detail, check [this page](https://github.com/raymondugv/HIS-Japan-Blog-Document#change-user-information)
3. Save

### Edit User
Check [this page](https://github.com/raymondugv/HIS-Japan-Blog-Document#change-user-information)
### Delete User
1. Select on `Trash` icon at the end of the user row that you want to delete.
2. Confirm delete chosen user on showing modal
3. Page reloaded and check if user account deleted.
## Role
View Role setting. Currently, only `Super Admin` can only change this setting.

This would be updated soon.
# Content Management

## Posts
Please check [this page](https://github.com/raymondugv/HIS-Japan-Blog-Document#posts) for more information

## Categories

### Create new Category
1. Click on `CREATE NEW` button on top right of the page
2. Fill the page with category information, in which:
   
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
2. Change or edit Category information.
3. Save & Update
### Delete Category
1. Click on `trash` icon at the end of the category row.
2. Confirm on the showing modal.
3. The page will reload, then check user check if Category deleted.
## Famous Theme

### Add new Famous Theme
1. Click on `CREATE NEW` button on top right of the page.
2. Fill the page with Famous Theme information, in which

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
2. Edit Famous Theme with new information.
3. `Save & Update`
### Delete Famous Theme
1. Click on `trash` icon of selected Famous Theme.
2. Confirm on showing modal.
3. Check if selected Famous Theme deleted or not.
## Special Features

### Add new Special Feature
1. Click `CREATE NEW` button.
2. Fill all the required field

| Field | Type     | Description                |
| :-------- | :------- | :------------------------- |
| Link | url | **Required**. URL of this Special Feature |
| Image | Image | **Required**. Image of this Special Feature |

3. Save
### Edit Special Feature
1. Click on `pencil` icon of selected Special Feature.
2. Update information.
3. Save.
### Delete Special Feature
1. Click on `trash` icon of selected Special Feature.
2. Confirm delete on showing modal.
3. Check if selected Special Feature deleted.

## Popular Search

### Create new Popular Search

### Edit Popular Search

### Delete Popular Search

## Advertising

### Create new Advertising Banner

### Edit Advertising Banner

### Delete Advertising Banner

# Administrator Tools

## Countries

### Create new Country Setting

## Site Setting