# Where is the JuiceFS

Hi, I am a co-founder of JuiceFS, and I often search the web for content about JuiceFS. Like you, I am a fan of JuiceFS, and organizing this list can help you and me more easily find and guide the parts we need in the future. If there's anything else that would be helpful, please let me know ;)

Below content may be in different languages, you could auto translate by Chrome or Edge, or other AI tools.

# Articles
- Jul 2024, [Introducing AuraFlow v0.1, an Open Exploration of Large Rectified Flow Models](https://blog.fal.ai/auraflow/), Fal team use the JuiceFS in AuraFlow to support distributed training on multi-modal data
- Jul 2024, [Sharing your Ollama models between Fly Machines using JuiceFS and Tigris](https://www.tigrisdata.com/blog/fly-tigris-juicefs/), Tigris is a new object store, low-latency, geo replicated, and no-egress fee. This is a case study about how to combine JuiceFS and Tigris as a file storage, store your Ollama data and share between multiple machines
- [Juicedata gives data processing giants a big squeeze on price](https://blocksandfiles.com/2024/07/05/juicedata-gives-data-processing-giants-a-big-squeeze-on-price/) (Me:thanks for your report🤟)

# Videos

- [JuiceFS CSI in Multi-Thousand Node Kubernetes Clusters for LLM Pre-Training](https://www.youtube.com/watch?v=DmzZHjl-vck) from [CNCF](https://www.youtube.com/@cncf), published at September 2024. Weiwei Zhu presents JuiceFS CSI Driver architecture and large-scale Kubernetes storage practices for LLM pre-training.
- [An introduction](https://www.youtube.com/watch?v=rlDtpGi0-nE) from [Pranali P. Lokhande](https://www.youtube.com/@pranalilokhande1036), published at August 2024
- [Open-Source Spotlight - JuiceFS](https://www.youtube.com/watch?v=6DfY_nm75CU) from [DataTalksClub](https://www.youtube.com/@DataTalksClub), published at July 2024
- [CoCalc Cloud Filesystems Demo](https://www.youtube.com/watch?v=uk5eA5piQEo) from [William Stein](https://www.youtube.com/@wstein389). The author created an infinitely scalable Cloud Filesystem (based on JuiceFS, KeyDB, and Google Cloud Storage) along with compute servers in Oregon and Italy. We clone the git source code, run some tests, illustrate how to do backups, use a Jupyter notebook, etc. using the shared filesystem. Published at June 2024 (Me:awesome work👏)
- [The Continuing Evolution of Research CI at the AMNH](https://www.youtube.com/watch?v=N9WHTCheO-4), a presentation from American Museum of Natural History, they mention JuiceFS is used in open storage network project, and get great success. (Me:thanks😍)
- [Cloud Empowerment: Unleashing the Potential of Memory Machine Cloud Snapshot Engine](https://www.youtube.com/watch?v=DKAZaMxErK4), MemVerge uses JuiceFS to accelerate BioTech pipeline and reduce cost, this video is published at May 2024
- [From Zero to Infinity：How AI-Powered Hedge Fund Build Cloud-Native AI Platform on Kubernetes](https://www.youtube.com/watch?v=aSwfT4oRrvI) from [CNCF](https://www.youtube.com/@cncf). This talk is presented by Yang Che from Aliyun and Zhiyi Li from Metabit Trading at KubeCon, published at October 2023
- [AI 플랫폼을 위한 스토리지 JuiceFS 도입기](https://www.youtube.com/watch?v=TmU7HqLHXVM) from [NAVER D2](https://www.youtube.com/@naver_d2), NAVER is the TOP1 search engine in Korea. This video is a short tailer in Korean, deep dive in detail, please check out [full blog post](https://d2.naver.com/helloworld/2184045).
- [How To Use JuiceFS To Store Data On DigitalOcean](https://www.youtube.com/watch?v=pdFzyflcRGA) from [Education Ecosystem](https://www.youtube.com/@EducationEcosystem), published at 2022
- [EP85 - JuiceFS on AWS](https://www.youtube.com/watch?v=PFNOcqiW4-M) from [Pahud Dev](https://www.youtube.com/@PahudDev). This video is Pahud who is AWS developer advocate, Charles and me talk in Mandarin, published at 2021

# Podcasts

- [核心又边缘的 Data Infra 企业——如何走出 AI 浪潮下的生存困境](https://podcasts.apple.com/us/podcast/%E6%A0%B8%E5%BF%83%E5%8F%88%E8%BE%B9%E7%BC%98%E7%9A%84-data-infra-%E4%BC%81%E4%B8%9A-%E5%A6%82%E4%BD%95%E8%B5%B0%E5%87%BA-ai-%E6%B5%AA%E6%BD%AE%E4%B8%8B%E7%9A%84%E7%94%9F%E5%AD%98%E5%9B%B0%E5%A2%83/id1687043102?i=1000664818135&l=zh-Hans-CN) from 持续集成, published at August 2024. Rui Su from JuiceFS and Xiaodan Zhuang from Greptime discuss data infrastructure companies, storage services, and AI-era product strategy.
- [存个文件还有这么多名堂？- 对话 JuiceFS 合伙人苏锐](https://podcasts.apple.com/us/podcast/%E5%AD%98%E4%B8%AA%E6%96%87%E4%BB%B6%E8%BF%98%E6%9C%89%E8%BF%99%E4%B9%88%E5%A4%9A%E5%90%8D%E5%A0%82-%E5%AF%B9%E8%AF%9D-juicefs-%E5%90%88%E4%BC%99%E4%BA%BA%E8%8B%8F%E9%94%90/id1687043102?i=1000637702865&l=zh-Hans-CN) from 持续集成, published at December 2023. Rui Su discusses distributed file systems, JuiceFS, and the Juicedata community and commercialization model.

# Projects

- [centminmod-juicefs](https://github.com/centminmod/centminmod-juicefs), a Centmin Mod setup guide and scripts for using JuiceFS with Cloudflare R2 object storage and a SQLite metadata engine on a LEMP stack.

# Mentions in social media

- Mar 2026, Sandbox0.ai mentioned JuiceFS on X: [persistent storage for sandbox sessions](https://x.com/Sandbox0AI/status/2033181466524631404). Sandbox0 says it uses JuiceFS so sandbox files can survive restarts and support checkpoints, forks, and long-lived sessions.
- Mar 2026, gerred mentioned JuiceFS on X: [portable volume mounts for agent sandboxes](https://x.com/devgerred/status/2030344019775979883). The reply names JuiceFS alongside CSI providers, Kubernetes persistent volumes, MicroVM developers, and FUSE for multi-read-write volume workflows.
- Feb 2026, Viga mentioned JuiceFS on X: [building a Drive integration with SandAgent](https://x.com/caedman_lan/status/2026469828761104838). The post describes exploring JuiceFS and SandAgent so LLM chats can interact with files more smoothly.
- Jove, co-founder of Timeplus mentioned JuiceFS on Linkedin. Timeplus is a vector database, they use the JuiceFS to [support tiered storage in Timeplus](https://www.linkedin.com/posts/jovezhong_juicefs-activity-7235418538633543681-SH4c/?utm_source=share)
