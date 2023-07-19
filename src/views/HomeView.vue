<template>
    <main
        class="mt-10 md:mt-1 flex flex-col-reverse gap-8 items-center md:flex-row md:gap-16 md:justify-center min-h-[65vh] md:min-h-[80vh]">
        <div class="space-y-2 text-center md:text-left px-10">
            <p class="text-amber-200">Hello World, I'm</p>
            <h1 class="text-4xl font-bold md:text-5xl text-white fadein-up">赖佳豪</h1>
            <div class="py-2">
                <h1 class="typewrite text-xl font-semibold text-transparent bg-clip-text bg-gradient-to-r from-slate-100 to-yellow-500 md:text-2xl fadein-up"
                    ref="typewriter">
                    <span class="wrap">{{ txt }}</span>
                </h1>
            </div>
            <p class="text-white pr-4 fade-in-from-left">欢迎来到我的个人主页 <span class="wave">👋🏼</span>
            </p>
            <br>
            <a href="http://www.laijiahao.cn/about" 
                class="fadein-bot fade-500 flex items-center py-2 px-4 mx-auto text-sm font-medium rounded-lg border transition duration-300 md:py-2.5 md:px-5 md:mx-0 text-amber-200 border-amber-200 hover:bg-amber-200 hover:bg-opacity-10 bg-transparent focus:outline-none w-fit">
                关于我</a>
            <a  href="https://space.bilibili.com/67268239" target="_blank"><button
                class="fadein-bot fade-500 flex items-center py-2 px-4 mx-auto text-sm font-medium rounded-lg border transition duration-300 md:py-2.5 md:px-5 md:mx-0 text-amber-200 border-amber-200 hover:bg-amber-200 hover:bg-opacity-10 bg-transparent focus:outline-none w-fit">
                <svg t="1689787410678" class="icon" viewBox="0 0 2299 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1676" width="32" height="32"><path d="M1775.714717 322.388293c6.017915 0.967165 53.194068-9.564186 55.128398-6.017915s24.071659 155.928471 18.591058 156.895636-44.059733 10.316425-44.059733 10.316425c-3.008957-20.525388-28.585095-147.868764-29.12241-161.194146m75.223935-14.614936l20.525388 163.021013c10.746276 0 53.194068-3.546271 57.170191-4.083585-6.017915-61.683627-16.549266-158.937428-16.549266-158.937428a158.185189 158.185189 0 0 0-61.146313 0m-40.620925 225.671805s92.740366-23.534345 126.376211-12.03583c16.979117 61.683627 48.143318 407.606265 51.152276 421.683887-21.492553 2.471644-90.268722 8.489558-95.749323 9.994037-4.513436-26.005989-81.779164-403.092829-81.779164-419.10478m343.880846-207.510598c5.480601 1.504479 54.591084-5.05075 55.128398-1.504479 0.967165 12.03583 6.017915 157.43295 0 157.970264l-44.597047 3.976122c-1.074628-20.095537-12.03583-146.901599-10.746276-160.441907m75.223935-3.976122l4.083585 161.194146c10.746276 0 52.656754 2.579106 57.17019 2.041792-1.074628-61.683627 0-158.937428 0-158.937428a271.236017 271.236017 0 0 0-61.253775-3.976122m-64.477659 216.000156s94.674695-12.465681 126.806062 2.579106c6.98508 72.214978 6.017915 408.358504 6.98508 422.651052-21.492553 0-90.268722 0.967165-95.749323 1.93433-0.967165-26.005989-39.546297-410.615222-38.041819-427.164488M1945.076033 125.086658c54.698547 278.650948 96.716488 754.925919 97.791116 785.552806 0 0 42.985106 0.967165 91.7732 3.976123-28.585095-300.250963-63.725419-780.072206-63.188105-795.224456-12.03583-13.540308-126.376211 6.017915-126.376211 6.017915M1824.395349 784.478179c-10.746276-78.12543-290.149463-166.889673-447.689876-138.304578 0 0-19.558223-171.940423-27.080617-339.474872-6.555229-143.355328-0.967165-282.734533 0-305.731564-10.746276-7.522393-123.904567 46.531377-185.05088 69.098557 0 0 73.182142 309.922612 126.376211 952.549943 0 0 84.680658 9.026872 230.077778-19.02091s317.874857-116.059785 303.367384-219.116576M1482.986147 925.146937l-24.501511-176.991172c6.017915-3.008957 156.895636 53.194068 172.907588 63.188105-2.471644 10.746276-148.406077 113.803067-148.406077 113.803067M610.603427 322.388293c6.017915 0.967165 53.731382-9.564186 55.128398-6.017915S689.803484 472.836163 684.322883 473.480939s-44.597047 9.994037-44.597047 9.994037c-3.008957-20.525388-28.585095-147.868764-29.122409-161.194146m75.223934-14.614936l20.525388 163.021013c10.746276 0 53.731382-3.546271 57.170191-4.083585-6.447766-61.683627-16.549266-158.937428-16.549266-158.937428a158.185189 158.185189 0 0 0-61.146313 0M644.776586 534.089938s92.740366-23.534345 126.37621-12.035829c16.979117 61.683627 48.143318 407.606265 51.152276 421.683887-21.492553 2.471644-90.268722 8.489558-95.749323 9.994037C722.472164 927.726044 644.776586 550.639204 644.776586 534.089938m343.880845-207.510597c5.480601 1.504479 54.591084-5.05075 55.128398-1.504479 0.967165 12.03583 6.017915 157.43295 0.537314 157.970263l-44.919435 3.976123c-1.074628-20.095537-11.605979-146.901599-10.746277-160.441907m75.223935-4.191048l4.083585 161.194146c10.746276 0 52.549292 2.579106 57.062728 2.041793-0.967165-61.683627 0-158.937428 0-158.937429A304.764399 304.764399 0 0 0 1063.881366 322.388293m-64.477658 216.000156s94.674695-12.465681 126.806061 2.579106c6.98508 72.214978 6.017915 408.358504 6.98508 422.651052-21.492553 0-90.268722 0.967165-95.749323 1.93433 0-26.005989-39.546297-410.615222-38.041818-427.164488M779.534892 125.086658c54.698547 278.650948 96.716488 754.925919 97.791115 785.552806 0 0 42.985106 0.967165 91.773201 3.976123C940.514113 614.364623 905.373789 134.543381 905.911103 118.209041c-12.03583-13.002994-126.376211 6.555229-126.376211 6.555228M659.284059 784.478179c-10.746276-78.12543-290.149463-166.889673-447.689876-138.304578 0 0-19.558223-171.940423-27.080617-339.474872-6.555229-143.355328-1.074628-282.734533 0-305.731564C174.519529-6.340303 61.146313 47.283616 0 69.850797c0 0 73.182142 309.922612 126.376211 952.549942 0 0 84.680658 9.026872 230.077778-19.020909S673.791532 887.53497 659.284059 784.478179M317.337543 925.146937l-24.608973-176.991172c6.017915-3.008957 157.003099 53.194068 173.01505 63.188105-2.471644 10.746276-148.406077 113.803067-148.406077 113.803067" fill="#1296db" p-id="1677"></path></svg> 我的B站</button></a>

        </div>
        <div class="flex justify-center md:justify-start fadein-right"><img alt="avatar" fetchpriority="high" width="300"
                height="300" decoding="async" data-nimg="1"
                class="w-10/12 md:h-auto rounded-full border-4 border-amber-200 pict"
                src="https://s1.ax1x.com/2023/07/20/pC7h8L4.jpg">
        </div>
    </main>
</template>

<script>
export default {
    name: 'HomeView',
    data() {
        return {
            toRotate: ["Web Developer", "Full-stack Engineer", "Tech Enthusiast"],
            period: 2000,
            txt: '',
            loopNum: 0,
            isDeleting: false,
        };
    },
    mounted() {
        this.$nextTick(() => {
            this.tick();
        });
    },
    methods: {
        tick() {
            let typewriter = this.$refs.typewriter;

            if (!typewriter) {
                return; // 如果无法获取 typewriter 元素，则结束函数
            }

            let i = this.loopNum % this.toRotate.length;
            let fullTxt = this.toRotate[i];

            // 根据当前状态，更新文本内容
            this.txt = this.isDeleting ? fullTxt.substring(0, this.txt.length - 1) : fullTxt.substring(0, this.txt.length + 1);
            typewriter.innerHTML = `<span class="wrap">${this.txt}</span>`;

            let that = this;
            let delta = 200 - Math.random() * 100;

            if (this.isDeleting) {
                delta /= 2; // 如果正在删除文本，则减少延迟时间
            }

            if (!this.isDeleting && this.txt === fullTxt) {
                delta = this.period; // 如果已经完全显示文本，则将延迟时间设置为固定的周期
                this.isDeleting = true; // 切换到删除文本的状态
            } else if (this.isDeleting && this.txt === '') {
                this.isDeleting = false; // 切换回添加文本的状态
                this.loopNum++; // 增加循环次数
                delta = 500; // 设置删除完整文本后的延迟时间
            }

            setTimeout(() => {
                that.tick(); // 递归调用 tick() 函数，进行下一次文本更新
            }, delta);
        }

    }
}
</script>

<style>
body {
    overflow-y: scroll;
    overflow-x: hidden;
}

.typewrite>.wrap {
    border-right: 0.08em solid #fff;
}

.wave {
    animation-name: wave-animation;
    animation-duration: 2.5s;
    animation-iteration-count: infinite;
    transform-origin: 70% 70%;
    display: inline-block
}

@keyframes wave-animation {
    0% {
        transform: rotate(0deg)
    }

    10% {
        transform: rotate(14deg)
    }

    20% {
        transform: rotate(-8deg)
    }

    30% {
        transform: rotate(14deg)
    }

    40% {
        transform: rotate(-4deg)
    }

    50% {
        transform: rotate(10deg)
    }

    60% {
        transform: rotate(0deg)
    }

    to {
        transform: rotate(0deg)
    }
}

.pict {
    box-shadow: 0px 0px 73px -9px rgba(255, 219, 112, 0.44);
    -webkit-box-shadow: 0px 0px 73px -9px rgba(255, 219, 112, 0.44);
    -moz-box-shadow: 0px 0px 73px -9px rgba(255, 219, 112, 0.44);
}

.fadein-up {
    opacity: 0;
    animation-name: fadeInUp;
    animation-duration: 0.5s;
    animation-fill-mode: forwards;
    animation-delay: 500ms;
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translate3d(0, 15px, 0);
    }

    to {
        opacity: 1;
        transform: translate3d(0, 0, 0);
    }
}

.fade-in-from-left {
    opacity: 0;
    animation: fadeInLeft 0.5s ease-out forwards;
    animation-delay: 500ms;
}

@keyframes fadeInLeft {
    0% {
        opacity: 0;
        transform: translateX(-100%);
    }

    100% {
        opacity: 1;
        transform: translateX(0);
    }
}

.fadein-right {
    opacity: 0;
    animation: fadeInRight 0.5s ease-out forwards;
    animation-delay: 500ms;
}

@keyframes fadeInRight {
    0% {
        opacity: 0;
        transform: translateX(100%);
    }

    100% {
        opacity: 1;
        transform: translateX(0);
    }
}

.fadein-bot {
    opacity: 0;
    animation: fadeInBot 0.5s forwards;
}

@keyframes fadeInBot {
    from {
        opacity: 0;
        transform: translate3d(0, -100%, 0);
    }

    to {
        opacity: 1;
        transform: translate3d(0, 0, 0);
    }
}

.fadein-1 {
    animation-delay: 200ms;
}

.fadein-2 {
    animation-delay: 400ms;
}

.fadein-3 {
    animation-delay: 600ms;
}

.fade-500 {
    animation-delay: 500ms;
}</style>
