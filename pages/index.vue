<template>
    <div style="height:100%">
       <my-header></my-header>
       <div class="container index">
            <div class="row">
                 <div class="col-xs-16 main">
                       <!-- 热门专题 -->
                       <div class="recommend-collection">
                           <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_1.jpg" alt="">
                               <span>故事</span>
                           </nuxt-link>
                             <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_2.jpg" alt="">
                               <span>摄影</span>
                           </nuxt-link>
                             <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_3.jpg" alt="">
                               <span>人文社科</span>
                           </nuxt-link>
                             <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_4.jpg" alt="">
                               <span>历史</span>
                           </nuxt-link>
                            <nuxt-link class="collection" to="/sign-in">
                           <img src="~/assets/img/c_5.jpg" alt="">
                               <span>读书</span>
                           </nuxt-link>

                           <nuxt-link class="more-collection" to="/">
                               更多热门专题
                               <i class="fa fa-angle-right"></i>
                           </nuxt-link>

                       </div>
                       <div class="split-line">
                       </div>
                       <!-- 文章列表 -->
                       <div class="list-container">
                           <ul class="note-list">
                               <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~/assets/img/note.jpg" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                            <nuxt-link to="/p/123" class="avatar">
                                                <img src="~/assets/img/default-avatar.jpg" alt="">
                                            </nuxt-link>
                                             <div class="info">
                                        <nuxt-link to="/u/123" class="nickname">
                                            测试用户
                                        </nuxt-link>
                                        <span class="time">
                                            04.12 10:18
                                        </span>
                                    </div>
                                </div>
                                   
                                    <div class="title">
                                        <nuxt-link to="/">
                                            佛系程序员的月薪5万指南
                                        </nuxt-link>
                                       
                                    </div>
                                    <div class="abstruct">
                                              再要：萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">
                                            社会与法
                                        </nuxt-link>
                                         <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                         </nuxt-link>
                                           <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                         </nuxt-link>
                                         <span>
                                             <i class="fa fa-heart"></i>
                                             20
                                         </span>
                                     
                                    </div>
                                </div>
                                
                               </li>
                               
                                   <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~/assets/img/note.jpg" alt="">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                            <nuxt-link to="/p/123" class="avatar">
                                                <img src="~/assets/img/default-avatar.jpg" alt="">
                                            </nuxt-link>
                                             <div class="info">
                                        <nuxt-link to="/u/123" class="nickname">
                                            测试用户
                                        </nuxt-link>
                                        <span class="time">
                                            04.12 10:18
                                        </span>
                                    </div>
                                </div>
                                   
                                    <div class="title">
                                        <nuxt-link to="/">
                                            佛系程序员的月薪5万指南
                                        </nuxt-link>
                                       
                                    </div>
                                    <div class="abstruct">
                                              再要：萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                              萨达所大所大所大所大所大所大所大所大所大所大所大所大所
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">
                                            社会与法
                                        </nuxt-link>
                                         <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                         </nuxt-link>
                                           <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                         </nuxt-link>
                                         <span>
                                             <i class="fa fa-heart"></i>
                                             20
                                         </span>
                                     
                                    </div>
                                </div>
                                
                               </li>
                           </ul>
                            <a href="#" class="load-more">阅读更多</a>
                       </div>
                 </div>
                 <div class="col-xs-offset-1 col-xs-7 aside">
                     侧边栏

                 </div>

            </div>
       </div>
    </div>
</template>
<script>
    import myHeader from  '../components/myHeader'
    export default {
        head:{
            title:'简书-创作你的创作',
            meta:[
                {charset:'utf-8'},
                {name:'keywords',content:'简书首页'},
                {name:'description',content:'简书首页'},
                {name:'author',content:'李志远'}
            ]
        },
        components:{
            myHeader
        },
        data () {
            return {
                name:'首页'
            }
        }
    }
</script>
<style>

</style>