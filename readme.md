# Snowboard Store (Snow 'n Stuff)

Snow 'n Stuff is a snowboard gear shop located in the fictional mountain town of Snowsville, VT.  The store was founded by the lateSnowey McSnowerson, a decorated US Army Veteran

---
## Opening the File

 - Pull Code and Open with Live Server

```bash
git pull https://github.com/jacobdefalco/snowboard-store
```
---
## Home page

 - Introduction to website
 ---
## Header and Footer

![image](https://user-images.githubusercontent.com/130497324/233464455-b5d12a75-c099-4198-941b-d8feb00b970a.png)
``` html
<header>
      <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Snow 'n Stuff</a>
          <img
            class="logo d-lg-none"
            src="images\Rustic_Minimal_Wedding_Print_Banner-removebg-preview.png"
            alt="Logo"
          />
          <img class="logo d-none d-lg-block" src="icons/logo.png" alt="Logo" />
```
- HTML code showing that my two logos switch depending on viewport 

![image](https://user-images.githubusercontent.com/130497324/233464576-6546d1ef-25fc-43eb-84a7-ea9f325468bd.png)
 - Properly carried both through every page of my site
    - Only making small changes when it made sense
---
![image](https://user-images.githubusercontent.com/130497324/233465000-84513af1-2b0d-45d3-8798-3997cf2b9f32.png)
 - Properly linked social media websites in the "Socials" drop down menu in header
 ---

![image](https://user-images.githubusercontent.com/130497324/233465389-c07a5d3d-3552-4ba4-9792-02408b22faa9.png)
![image](https://user-images.githubusercontent.com/130497324/233465563-ed2787e5-795f-4551-81fb-6dd00c759865.png)
 - Created Login & Register Pages also accessible through the header but under the "Account" tab
 - "How Did You Hear About Us?" radio buttons
---
 ![image](https://user-images.githubusercontent.com/130497324/233473351-8693c144-8d86-40ae-b8ee-7460f754e5d3.png)
 - Full view of 1/8 product pages
   - Proper discounted prices calculated

---
![image](https://user-images.githubusercontent.com/130497324/233474313-1cff5512-d759-402a-b803-ee1cef623bbb.png)
- Side Nav bar to travel within the product pages
---
![image](https://user-images.githubusercontent.com/130497324/233475647-59517f49-c690-4fb8-a40e-eb30228f1cff.png)
- Full product page view.  Notice the checkout button only appears on the product pages.
---
![image](https://user-images.githubusercontent.com/130497324/233475939-dbaea01a-61ea-448d-aef8-365483a05766.png)
- Checkout page with items properly tallied and promo code added.
    - Drop down containing all of the worlds countries and all US states and territories 
    
---
![image](https://user-images.githubusercontent.com/130497324/233476582-248b24e9-bb0f-43b5-ae53-120aeac196fd.png)
- Payment section positioned right beneath previous picture
```HTML
<div class="col-md-6">
                <label for="cc-number" class="form-label">Credit card number</label>
                <input type="text" class="form-control" id="cc-number" placeholder="" required maxlength="16"/>
                <div class="invalid-feedback">Credit card number is required</div>
              </div>
            </div>
            <div class="row justify-content-center">
              <div class="col-md-3">
                <label for="cc-expiration" class="form-label">Expiration</label>
                <input type="text" class="form-control" id="cc-expiration" placeholder="" required />
                <div class="invalid-feedback">Expiration date required</div>
              </div>

              <div class="col-md-3">
                <label for="cc-cvv" class="form-label">CVV</label>
                <input type="text" class="form-control" id="cc-cvv" placeholder="" required maxlength="3" />
                <div class="invalid-feedback">Security code required</div>
              </div>
```
- HTML code showing maxlength attributes being added to CC# and CVV input fields