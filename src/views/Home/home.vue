<template>
  <div class="Home">
       <div class="wrapper">
        <div class="header">
          <div class="icon-menu">
              <svg width="36" height="35" viewBox="0 0 36 35" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
              <rect x="0.3125" width="35.3528" height="35" fill="url(#pattern0)"/>
              <defs>
              <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
              <use xlink:href="#image0" transform="translate(0 -0.00504031) scale(0.00195312)"/>
              </pattern>
              <image id="image0" width="512" height="512" xlink:href="data:image/png;base64,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"/>
              </defs>
              </svg>
          </div>
          <div class="title-header">
            <h2>Foods Items</h2>
          </div>
          <div class="icon-search">
              <div>
                   <img src="@/assets/magnifying-glass.svg" id="show-btn" @click="$bvModal.show('bv-modal-example')">
                  <b-modal id="bv-modal-example" hide-footer >
                    <template v-slot:modal-title style="border: 10px solid black;">
                      <h2> Product <code> Search</code> </h2>
                    </template>
                    <div class=" text-center">
                         <b-form-group>
                            <b-input v-model="search"  placeholder="Search Product" style="margin-bottom:1em;margin-top:1em;"></b-input>
                              <b-form-radio-group
                                v-model="radio"
                                :options="optionRadio"
                                name="radio-inline"
                                style="margin-bottom:2em;"
                              ></b-form-radio-group>
                        </b-form-group>
                    </div>
                    <b-button class="mt-3" variant="primary" block @click="$bvModal.hide('bv-modal-example')">Search</b-button>
                  </b-modal>
            </div>
          </div>
        </div>
      </div>
      <div class="wrapper" id="header-cart">
          <div class="header-cart">
            <div class="title-cart">
              <h2>Cart <span> {{ listCHart.length }} </span></h2>
            </div>
          </div>
      </div>
      <!-- header cart -->
      <div class="wrapper" id="cart" >
          <div class="cart-customer">
            <div v-if="listCHart.length == 0">
                <div class="cart">
                  <img src="@/assets/food-and-restaurant.png">
                </div>
                <div class="desc-cart" v-if="listCHart.length == 0">
                  <h2>You cart is empty</h2>
                  <p>Please add some items from the menu</p>
                </div>
            </div>
            <div  v-if="listCHart.length >= 1" hidden>
                <div class="cart">
                  <img src="@/assets/food-and-restaurant.png">
                </div>
                <div class="desc-cart" v-if="listCHart.length >= 1" hidden>
                  <h2>You cart is empty</h2>
                  <p>Please add some items from the menu</p>
                </div>
            </div>
              <!-- cart  -->
              <div class="wrapper-cart" v-for="items in listCHart" :key="items">
                  <img :src="items.image" id="cart-img" class="img-thumbnail">
                  <h4> {{items.name}} </h4>
                  <b-button-group>
                      <b-button variant="success" style="font-weight: 900;" v-on:click = 'value -= 1'>-</b-button>
                      <div class="form-control total" value ="1" > {{ value }} </div>
                      <b-button variant="success" style="font-weight: 900;" v-on:click = 'value += 1'>+</b-button>
                  </b-button-group>
                  <p> {{ items.price }}</p>
              </div> 
          </div> 
      </div>
      <!-- s -->
      <div class="wrapper" id="sidebar">
         <div class="sidebar">
          <div class="sidebar-action">
            <div class="icon-menus"> 
                <img src="@/assets/fork.png"> <span>Menus</span>
            </div>
            <div class="icon-history">
              <img src="@/assets/clipboard.png"> <span>History</span>
            </div>
            <div>
                <img src="@/assets/add.svg" @click="$bvModal.show('CRUD')" >
 
                <b-modal id="CRUD" hide-footer header-border-variant="primary">
                  <template v-slot:modal-title>
                    <h3> "LeBlanc Cafe" <code>SETUP</code> </h3>
                  </template>
                  <div class="d-block text-center">
                    <h2>Hello welcome back! </h2> <br>  <p style="float:left;"> What do you want?</p>
                  </div>
                  <b-button variant="primary" class="mt-3" block @click="$bvModal.show('bv-modal-AddData')"> <h5>ADD PRODUCT</h5></b-button>     
                   <b-button variant="outline-primary" class="mt-3" block @click="$bvModal.show('bv-modal-UpdateData')"> <h5>UPDATE PRODUCT</h5> </b-button> 
                    <b-button variant="outline-primary" class="mt-3" block @click="$bvModal.show('bv-modal-DeleteData')"><h5>DELETE PRODUCT</h5> </b-button> 
                </b-modal>
            </div>        
          </div>
        </div>
      </div>
      <!-- GET PRODUCT -->
      <b-row id="row">
       <div id="product"  v-for="data in product" :key="data.id"
            v-on:click= "addCart(data)"> 
                <Product
                    :images="data.image"
                    :names="data.name"
                    :price="data.price"
                />
        </div>
      </b-row>
              <!-- modal Add Data -->
              <b-modal  id="bv-modal-AddData" size="lg" header-bg-variant="primary" header-text-variant="white" header-border-variant="dark"
              footer-border-variant="dark">
                  <template v-slot:modal-title>
                        <h2>Add Product </h2>
                  </template>
                  <template v-slot:modal-footer>
                      <b-button variant="outline-danger" @click="clean"> <h5>Cancel</h5></b-button>
                      <b-button variant="primary" style="width:16em; margin:0 25px 0 15px;" @click="save"><h5 style="font-weight:700;">Add</h5></b-button>
                  </template>
                  <div class="modal-body">
                    <h5 style="margin-top:-10px;">Name</h5>
                    <b-form-input v-model="form.name" id="input1" placeholder="name product"> </b-form-input>
                    <h5 style="margin-top:18px;">Price</h5>
                    <div class="input-group mb-3" id="input3">
                         <div class="input-group-prepend">
                           <span class="input-group-text">Rp.</span>
                         </div>
                         <b-form-input v-model="form.price" placeholder="entry price product"> </b-form-input>
                       </div>
                    <h5 style="margin-top:18px;">Image</h5>
                    <div class="input-group" id="input2">
                         <div class="custom-file">
                           <input v-model="form.image" type="text" class="form-control" id="inputGroupFile04" aria-describedby="inputGroupFileAddon04" placeholder="link url-image">
                         </div>
                         <div class="input-group-append">
                           <button class="btn btn-outline-primary" type="button" id="inputGroupFileAddon04" >OK! </button>      
                         </div>
                       </div>
                    <h5 style="margin-top:18px;">Category</h5>
                    <div id="input4">
                        <b-form-select v-model="form.category" :options="options"  v-if="selected == null">
                              <h2>{{ selected }}</h2>
                        </b-form-select> 
                  </div>
              </div>
              </b-modal>
               <!-- MODAL UPDATE PRODUCT  -->
               <b-modal  id="bv-modal-UpdateData" size="lg" header-bg-variant="primary" header-text-variant="white" header-border-variant="dark"
              footer-border-variant="dark">
                  <template v-slot:modal-title>
                        <h2>Update Product </h2>
                  </template>
                  <template v-slot:modal-footer>
                      <b-button variant="outline-danger" @click="clean"> <h5>Cancel</h5></b-button>
                      <b-button variant="primary" style="width:16em; margin:0 25px 0 15px;" @click="Update"><h5 style="font-weight:700;">Update</h5></b-button>
                  </template>
 
                  <div class="modal-body">
                    <div class="input-group" id="input2" style="width: 40%; float:right; border:1px solid black; border-radius:5%;">
                         <div class="custom-file">
                           <b-form-input v-model="update.id" placeholder="type id product"> </b-form-input>
                         </div>
                         <div class="input-group-append">
                           <button class="btn btn-outline-primary" type="button" @click="searchID" >Search</button>      
                         </div>
                       </div> 
                    <h5 style="margin-top: 40px;">Name</h5>
                    <b-form-input v-model="update.name" id="input2" placeholder="name product"> </b-form-input>
                    <h5 style="margin-top:18px;">Price</h5>
                    <div class="input-group mb-3" id="input3">
                         <div class="input-group-prepend">
                           <span class="input-group-text">Rp.</span>
                         </div>
                         <b-form-input v-model="update.price" placeholder="entry price product"> </b-form-input>
                       </div>
                    <h5 style="margin-top:18px;">Image</h5>
                    <div class="input-group" id="input2">
                         <div class="custom-file">
                           <input v-model="update.image" type="text" class="form-control" placeholder="link url-image">
                         </div>
                         <div class="input-group-append">
                           <button class="btn btn-outline-primary" type="button">OK! </button>      
                         </div>
                       </div>
                    <h5 style="margin-top:18px;">Category</h5>
                    <div id="input4">
                       <input v-model="update.category" type="text" class="form-control" placeholder="category id">
                  </div>
              </div>
              </b-modal> 
              <!-- MODAL DELETE PRODUCT -->
                <b-modal id="bv-modal-DeleteData" hide-footer header-bg-variant="primary" header-text-variant="white" header-border-variant="dark">
                  <template v-slot:modal-title>
                    <h4>Delete Product</h4>
                  </template>
                  <div class="d-block text-center">
                     <b-input-group prepend="ID" class="mt-3"> 
                       <b-form-input v-model="deleteId">
                       </b-form-input>
                      </b-input-group>
                  </div>
                  <b-button variant="outline-danger" class="mt-3" block @click="Delete" style="width:15em;display:block; margin:20px auto;"> <h4> Delete </h4></b-button>
                </b-modal>
  </div>
</template>
 
<script>
import Product from '../../components/product'
import axios from 'axios'
 
export default {
  name : 'product',
  components : {
    Product,
  },
  data(){
    return{
        product: [],
        listCHart : [],
        search :  '',
        selected: null,
        options: [
          { value: null, text: 'Please select an category',disabled: true},
          { value: '1', text: 'Drink' },
          { value: '2', text: 'Food' },
          { value: '3', text: 'Fast Food' },
        ],
        radio: '',
        optionRadio: [
          {text: 'ID Name'},
          {text: 'Name Menu'},
          {text: 'Category'},
          {text: 'Price'}
        ],
        form: {
          name: '',
          price: '',
          image: '',
          category: ''
        }, 
        value : 1,
        update: {
          id: "",
          name: "",
          price: "",
          image: "",
          category: ""
        },
        deleteId: "",
    }
  },
  mounted() {
    this.load()
 
  },
  methods: {
    load(){
        axios.get('http://localhost:8000/product')
        .then(res => {
        this.product = res.data
      }).catch ((err) => {
        console.log(err)
      })
    },
    save(){
      axios.post('http://localhost:8000/product', this.form) 
      .then((res) => {
        alert('Product Sucessfully Saved!', res)
        this.load()
        this.form = []
        this.clean()
      })
      .catch(err => {
        console.log(err)
      })
    },
    Update(){ 
        axios.put('http://localhost:8000/product', {
          id: this.update.id,
          name: this.update.name,
          price: this.update.price,
          category: this.update.category
        })
        .then((res) => {
        alert('Product was Updated!', res)
        this.load()
        this.form = []
        this.clean()
      })
      .catch(err => {
        console.log(err)
      })
    },
    Delete(){
      axios.delete('http://localhost:8000/product/delete/'+this.deleteId) 
        .then(res => {
          console.log(res)
          alert("Success delete product")
        })
    },
    clean(){
      this.$bvModal.hide('bv-modal-AddData')
      this.$bvModal.hide('bv-modal-UpdateData')
    },
    addCart(data){
      this.listCHart.push(data)
    },
 
    // computed: {
    //   filterdProduct : () => {
    //     return this.load.filter(() => {
    //       return Boolean;
    //     })
    //   }
    // }
   }
}
</script>
 
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
   background-color: white ;
   width: 73%;
   height: 4.5em;
   display: flex;
   flex-direction: row;
   justify-content: space-between;
   align-items: center;
   box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
   position: fixed;
   z-index: 1;
   border-radius: 8px;
    border-bottom:#007BFF solid;
    box-shadow: 10px 10px rgba(144, 144, 144, 0.212);
 }
 .icon-menu {
   padding-left: 40px;
   cursor: pointer;
 }
 .icon-search {
   padding-right: 30px;
   cursor: pointer;
 }
 
 .header-cart {
   width: 27.6%;
   height: 4.5em;
   margin-left:58.6em;
   background-color: white ;
   box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
   z-index: 1;
   text-align: center;
   border-radius: 8px;
    border-bottom:#007BFF solid;
    box-shadow: 10px 10px rgba(144, 144, 144, 0.212);
    position: fixed;
 }
 .title-cart h2 {
   padding-top: 12px;
 }
 .header-cart span {
   background-color:#57CAD5;
   color: white;
   border-radius: 20%;
 }
 .sidebar {
   width: 4em;
   background-color: white;
   padding-top: 7em;
   margin-left: 1.5em;
   padding-bottom: 12em;
   border-radius: 8px;
   /* border: 1px gray solid; */
    border-bottom:#007BFF solid;
    box-shadow: 10px 10px rgba(144, 144, 144, 0.212);
    position: fixed;
    cursor: pointer;
 }
 .sidebar-action {
   display: flex;
   flex-direction: column;
   align-items: center;
   text-align: center;
   font-weight: 500;
   font-size: 16px;
 }
 .sidebar-action img:hover {
   transform: scale(1.1);
 }
 .sidebar-action img {
  padding: 1.4em;
 }
 #cart {
   width: 21.5em ;
   height: 90em;
   margin: 4.8em auto auto 58.8em;
   position: fixed;
   background-color: white;
   border-radius: 8px;
   box-shadow: -10px 10px rgba(144, 144, 144, 0.212);
   z-index: 1;
 }
 .cart-customer {
   display: flex;
   flex-direction: column;
   justify-content: center;
   align-items: center;
   text-align: center;
 }
 /* MODEL STYLING */
  #bv-modal-AddData h5 {
   font-family: sans-serif;
  }
  #bv-modal-AddData .modal-body #input1, #input2, #input3, #input4  {
    box-sizing: border-box;
    box-shadow: 0px 4px 6px rgba(228, 214, 214, 10);
 }
  #row {
    width: 80%;
    margin-left: 5em;
    padding-top: 4.5em;
  }
  #UpDown {
    margin-top: 2em;
  }
  .wrapper-cart {
    display: flex;
    flex-direction: row;
  }
  .wrapper-cart img {
    width: 20px;
  }
</style>