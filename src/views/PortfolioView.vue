<script>
    export default {
        data() {
            return {
                activeTab: 1,
                items: [
                    {
                        id: 1,
                        name: 'Personal Website',
                        imageUrl: 'portfolio_v1',
                        status: '个人主页 暗黑色主题只有前端部分.',
                        tech: 'VueJS 3, Tailwind',
                        github: 'https://github.com/rakha-elctrnx/Portofolio-v2',
                        demo: 'https://bagasrakha.netlify.app/'
                    },
                    {
                        id: 2,
                        name: '个人主页',
                        imageUrl: 'homepage',
                        status: '个人主页 也是使用新技术栈的主要项目.',
                        tech: 'VueJS 3, TypeScript, Element UI',
                        github: 'https://github.com/rakha-elctrnx/muslim-companion',
                        demo: 'http://www.zhouyi.run/#/About'
                    },
                    {
                        id: 3,
                        name: '个人博客系统',
                        imageUrl: 'blog',
                        status: '全栈个人博客系统[前台]，包含前端博客展示、后台管理、node后端服务。包括前后台完整基础功能',
                        tech: 'VueJS 2, JavaScript, Element UI, Express.js, Mysql',
                        github: 'https://gitee.com/Z568_568/all-blog-sys.git',
                        demo: 'http://blog.zhouyi.run/#/'
                    },
                    {
                        id: 4,
                        name: '个人博客系统',
                        imageUrl: 'admin-blog',
                        status: '全栈个人博客系统[后台]，包含前端博客展示、后台管理、node后端服务。包括前后台完整基础功能.',
                        tech: 'VueJS 2,D2-admin, JavaScript, Element UI, Express.js, Mysql',
                        github: 'https://gitee.com/Z568_568/all-blog-sys.git',
                        demo: 'http://admin.blog.zhouyi.run/#/index'
                    },
                    {
                        id: 5,
                        name: 'Vue3-Antd-Plus管理系统',
                        imageUrl: 'ZY-admin',
                        status: '👍 提供了一个基于最新的技术栈的完整开发模板,旨在帮助初学者更快地入门并加入团队开发。该模板包含了一系列功能模块，如大屏展示、自定义主题、角色用户、菜单授权、数据权限和系统参数等，并且所有模块都经过了完整的组件封装.',
                        tech: 'Vue 3、Vite、Ant Design Vue 3、JavaScript、Pinia,vue-router',
                        github: 'https://gitee.com/Z568_568/vue3-antd-plus',
                        demo: 'null'
                    },
                    {
                        id: 5,
                        name: 'Vue3-Antd-Plus大屏可视化',
                        imageUrl: 'max',
                        status: '基于最新的技术栈的完整开发模板大屏可视化.',
                        tech: 'Vue 3、Vite、Ant Design Vue 3、JavaScript、Pinia,vue-router',
                        github: 'https://gitee.com/Z568_568/vue3-antd-plus',
                        demo: 'null'
                    }, {
                        id: 5,
                        name: 'Vue3-Antd-Plus系统前台',
                        imageUrl: 'ZY-client',
                        status: '基于最新的技术栈的完整开发模板前台.',
                        tech: 'Vue 3、Vite、Ant Design Vue 3、JavaScript、Pinia,vue-router',
                        github: 'https://gitee.com/Z568_568/vue3-antd-plus',
                        demo: 'null'
                    },
                    {
                        id: 5,
                        name: '个人文件管理+图床管理服务系统',
                        imageUrl: 'files',
                        status: '🎉轻量级个人文件管理、图床管理服务系统，对文本文件、图片、视频、音频、音乐等各类文件的存储管理.',
                        tech: 'node.js、mysql、vue2',
                        github: 'https://gitee.com/Z568_568/zy.files.sys.git',
                        demo: 'http://files.zhouyi.run/#/'
                    },
                    {
                        id: 5,
                        name: 'ZY.Hexo.Blog响应式简约清爽款个人博客',
                        imageUrl: 'hexo',
                        status: 'Hexo博客框架搭建响应式、简约清爽款个人博客站点，基于Ocean主题 做了改动,增加了分类、标签、音乐菜单、页脚个人资源和站点运行时间等配置.',
                        tech: 'Hexo',
                        github: 'https://gitee.com/Z568_568/zy-hexo-blog.git',
                        demo: 'http://hexo.blog.zhouyi.run/'
                    },
                    {
                        id: 5,
                        name: '个人简历html单页模板',
                        imageUrl: 'resume',
                        status: '个人简历html单页模板，个人简历, 求职, 工作经历, 教育经历, 技能, 荣誉与奖项, 社交媒体, 联系方式.',
                        tech: 'Html, JavaScrip, Css3',
                        github: 'https://gitee.com/Z568_568/zhouyi.resume.git',
                        demo: 'http://resume.zhouyi.run/'
                    },
                    {
                        id: 5,
                        name: 'ZY.Node.Mongodb构建REST API接口服务基础样板',
                        imageUrl: 'preview',
                        status: 'REST API 开发的轻量级样板。集成了Swagger UI、JWT、session、发送邮箱验证、日志管理、统一的预定义状态码响应格式等，对于为前端平台构建纯净的Web API非常有用。.',
                        tech: ' Node.js、Express.js, MongoDB',
                        github: 'https://gitee.com/Z568_568/node.mongodb.git',
                        demo: 'null'
                    },
                ]
            };
        }
    }
</script>
<template>
    <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
        <article data-page="about">
            <header>
                <div
                        class="text-2xl font-bold text-white mb-10 fadein-bot title-section flex items-center justify-center flex-col">

                    <h4>Personal project</h4>
                    <!--          <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate"></div>-->
                    <h4 class="text-base font-normal text-transparent bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300">
                        Explore the open source projects I've worked on so far</h4>

                </div>
            </header>
            <section>
                <div>
                    <div class="grid grid-cols-1 gap-4 pb-32 md:grid-cols-3 md:gap-3 xl:grid-cols-3 xl:gap-3 2xl:gap-5 fade-zoom-in">
                        <div v-for="item in items" :key="item.id">
                            <div
                                    class="item-card flex flex-col items-center gap-2 rounded bg-[#1e1e1f] hover:bg-[#282828] border border-[#383838] rounded-xl text-amber-50 md:gap-3 px-5 py-5 lg:px-5 ">
                                <div class="flex h-12 w-12 items-center justify-center p-0 h-full w-full lg:p-0 zoom-in">
                                    <img alt="HTML" loading="lazy" decoding="async" data-nimg="1"
                                         class="drop-shadow-xl rounded rounded-xl"
                                         :src="'/img/portfolio-' + item.imageUrl + '.png'">
                                </div>
                                <div class="w-full flex flex-col gap-2 items-center text-sm md:text-base lg:text-lg">
                                    <div class="title-text font-medium text-secondary">{{ item.name }}
                                    </div>
                                    <div class="w-full text-left text-[10px] text-[#c1c1c1] md:text-xs lg:text-sm">
                                        {{ item.status }}
                                    </div>
                                    <div class="w-full mt-4 text-normal text-sm text-left text-amber-200">
                                        {{ item.tech }}
                                    </div>
                                    <div class="w-full flex justify-end">
                                        <div class="flex cursor-pointer items-end gap-2 text-primary">
                                            <a v-if="item.github !== 'null'"
                                               :href="item.github" target="_blank" rel="noreferrer"
                                               title="查看源码" class="transition-all hover:text-accent">
                                                <svg stroke="currentColor"
                                                     fill="none" stroke-width="2" viewBox="0 0 24 24"
                                                     stroke-linecap="round" stroke-linejoin="round"
                                                     height="16" width="16" xmlns="http://www.w3.org/2000/svg">
                                                    <path
                                                            d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22">
                                                    </path>
                                                </svg>
                                            </a>
                                            <a v-if="item.demo !== 'null'" :href="item.demo" target="_blank"
                                               rel="noreferrer"
                                               title="查看" class="transition-all hover:text-accent">
                                                <svg stroke="currentColor"
                                                     fill="none" stroke-width="2" viewBox="0 0 24 24"
                                                     stroke-linecap="round" stroke-linejoin="round"
                                                     height="18" width="18" xmlns="http://www.w3.org/2000/svg">
                                                    <path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path>
                                                    <polyline points="15 3 21 3 21 9"></polyline>
                                                    <line x1="10" y1="14" x2="21" y2="3"></line>
                                                </svg>
                                            </a></div>
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
    .item-card:hover {
        transition: transform 0.3s ease;
        transform: translateY(-8px);
    }

    svg:hover {
        stroke: #ffdb70;
    }

    @keyframes fadeZoomIn {
        0% {
            opacity: 0;
            transform: scale(0.5);
        }
        100% {
            opacity: 1;
            transform: scale(1);
        }
    }

    /* Menggunakan animasi pada elemen yang diinginkan */
    .fade-zoom-in {
        animation: fadeZoomIn 1s ease-in-out;
    }
</style>
