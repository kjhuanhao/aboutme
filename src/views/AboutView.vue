<script>
    export default {
        data() {
            return {
                activeTab: 1,
                tech: [
                    {
                        id: 1,
                        name: 'HTML',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/1051/1051277.png',
                        status: '掌握'
                    },
                    {
                        id: 2,
                        name: 'CSS',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/732/732190.png',
                        status: '掌握'
                    },


                    {
                        id: 4,
                        name: 'Javascript',
                        imageUrl: 'https://cdn.icon-icons.com/icons2/2415/PNG/512/javascript_original_logo_icon_146455.png',
                        status: '掌握'
                    },
                    {
                        id: 7,
                        name: 'VueJS',
                        imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-vue-282497.png?f=webp',
                        status: '了解'
                    },
                    {
                        id: 8,
                        name: 'Pytgon',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/5968/5968350.png',
                        status: '熟练'
                    },
                    {
                        id: 31,
                        name: 'Java',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/226/226777.png',
                        status: '熟练'
                    },
                    {
                        id: 31,
                        name: 'linux',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/6124/6124995.png',
                        status: '了解'
                    },
                ],
                tools: [
                    {
                        id: 1,
                        name: 'Git',
                        imageUrl: 'https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png',
                        status: 'Version Control'
                    },
                    {
                        id: 2,
                        name: 'GitHub',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/25/25231.png',
                        status: 'Git Hosting'
                    },
                    {
                        id: 3,
                        name: 'NPM',
                        imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-npm-3-1175132.png',
                        status: 'Package Manager'
                    },
                    {
                        id: 4,
                        name: 'MySQL',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/5968/5968313.png',
                        status: 'Database'
                    },
                    {
                        id: 5,
                        name: 'MongoDB',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/2906/2906274.png',
                        status: 'Database'
                    },
                    {
                        id: 7,
                        name: 'Hexo',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/2065/2065254.png',
                        status: '博客构建工具'
                    },
                    {
                        id: 8,
                        name: 'Docker',
                        imageUrl: 'https://cdn-icons-png.flaticon.com/512/5969/5969059.png',
                        status: '容器工具'
                    }
                ]
            };
        }
    }
</script>
<template>
    <div
            class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
        <article data-page="about">

            <header>
                <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
                    About Me &nbsp;
                    <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
                         data-aos-duration="600"></div>
                </div>
            </header>

            <section
                    class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
                <div class="flex justify-center">
                    <img class="w-9/12 rounded-full mb-3 fadein-up pict"
                         src="https://s2.loli.net/2023/07/20/eBLdFcXfROUIaoy.jpg" alt="Foto">
                </div>
                <div class="md:w-7/12">
                    <ul class="mb-3 md:mb-7 fadein-left fadeins-1">
                        <li  class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· Hi! 我是赖佳豪，一名目前即将大二的学生，我的所学的专业是会计学</li>
                        <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">· 00后 热爱编程 持续学习中 追求技能不断提高</li>
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· 热衷于学习技术类知识，不断充实和提高自己，对新技术有强烈的学习欲望</li>
                        <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">· 同时，是一个B站的视频博主，目前1W+的粉丝</li>
                    </ul>
                    <ul class="mb-3 md:mb-7 fadein-left fadeins-2">
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">· 认为生活的本质是一场历程</li>
            
                        <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">
                            · 如果你有任何关于技术交流或者生活分享的想法
                        </li>
                        <li class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent">
                            · 欢迎与我交流，一同探讨，共同成长！
                        </li>
                       <!-- <li class="bg-clip-text bg-gradient-to-l from-slate-100 to-amber-300 text-transparent">扫我微信/QQ加我吧</li>
                        <a target="_blank"
                           href="http://www.zhouyi.run:3001/api/v1/files/preview?p=6f0b0673e1a42ba952edfca76a557ca.png&amp;&amp;mimetype=image/png"
                        ><img width="100" height="100"
                              src="http://www.zhouyi.run:3001/api/v1/files/preview?p=6f0b0673e1a42ba952edfca76a557ca.png&amp;&amp;mimetype=image/png"
                        ></a><a target="_blank"
                                href="http://www.zhouyi.run:3001/api/v1/files/preview?p=d110c3b8573988728c2685d9a5889d2.png&amp;&amp;mimetype=image/png"
                    ><img width="100"
                          height="100"
                          src="http://www.zhouyi.run:3001/api/v1/files/preview?p=d110c3b8573988728c2685d9a5889d2.png&amp;&amp;mimetype=image/png"
                    ></a>-->
                    </ul>
                    <!--                    <p class="mb-3 fadein-left fadeins-2">-->
                    <!--                        &nbsp; &nbsp; &nbsp;-->
                    <!--                        我擅长使用各种前端技术，包括HTML、CSS、JavaScript等，并熟悉流行的前端框架和工具，如React、Vue.js和Webpack。我能够将设计师的视觉概念转化为现实，并确保网站在各种浏览器和设备上的兼容性。-->

                    <!--                        如果您正在寻找一位有经验、有创意的前端开发者，我很乐意为您提供服务。请通过下方提供的联系方式与我取得联系，让我们一起创造出令人印象深刻的网站吧！-->
                    <!--                    </p>-->
                </div>

            </section>

        </article>
    </div>

    <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
        <article data-page="about">
            <header>
                <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
                    <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate" data-aos="zoom-in-left"
                         data-aos-duration="600"></div>
                    &nbsp; Skills
                </div>
            </header>
            <section>
                <div>
                    <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5">
                        <li class="mr-2">
                            <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                                    :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 1 }"
                                    @click="activeTab = 1">Tech Stack
                            </button>
                        </li>
                        <li class="mr-2">
                            <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                                    :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2 }"
                                    @click="activeTab = 2">Tools
                            </button>
                        </li>
                    </ul>
                </div>
                <div v-show="activeTab === 1">
                    <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
                        <div v-for="item in tech" :key="item.id">
                            <div
                                    class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in" v-if="item.imageUrl">
                                    <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                                         class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                                         :src="item.imageUrl" style="color: transparent;">
                                </div>
                                <div class="flex items-center text-sm md:text-base lg:text-lg">
                                    <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">
                                        {{ item.name }}
                                    </div>
                                    <div
                                            class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                                        {{ item.status }}
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div v-show="activeTab === 2">
                    <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
                        <div v-for="item in tools" :key="item.id">
                            <div
                                    class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                                    <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                                         class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                                         :src="item.imageUrl" style="color: transparent;">
                                </div>
                                <div class="flex items-center text-sm md:text-base lg:text-lg">
                                    <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">
                                        {{ item.name }}
                                    </div>
                                    <div
                                            class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                                        {{ item.status }}
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </article>
    </div>
</template>

<style>
    .fadein-left {
        opacity: 0;
        font-size: 1.1rem;
        line-height: 2.2rem;
        animation: fadeInLeft 0.5s ease-out forwards;
    }

    @keyframes fadeInLeft {
        0% {
            opacity: 0;
            transform: translateX(100%);
        }

        100% {
            opacity: 1;
            transform: translateX(0);
        }
    }

    .fadeins-1 {
        animation-delay: 500ms;

    }

    .fadeins-2 {
        animation-delay: 800ms;
    }

    .img-tech,
    .tech {
        transition: transform 0.3s ease;
    }

    .item-tech:hover .img-tech {
        transform: scale(1.3);
    }

    .item-tech:hover .tech {
        transform: translateY(-12px);
    }

    .item-tech:hover .status-tech {
        opacity: 1;
    }
    .pict {
        box-shadow: 0px 0px 43px -9px rgba(255, 219, 112, 0.44);

    }
</style>
