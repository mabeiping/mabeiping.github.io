<template>
  <div class="blog-profile-container">
    <div class="profile-card">
      <div class="profile-header">
        <div class="avatar">
          <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
            <circle cx="12" cy="7" r="4"></circle>
          </svg>
        </div>
        <h3 class="profile-name">小马Office</h3>
        <p class="profile-title">实用工具分享</p>
      </div>
      
      <div class="profile-intro">
        <p class="intro-text">
          欢迎来到小马Office工具站！这里汇集了各种实用的办公工具，帮助您提高工作效率。从文本处理到数据分析，从格式转换到文件管理，我们为您提供一站式解决方案。
        </p>
      </div>
      
      <div class="social-links">
        <h4 class="section-title">关注我们</h4>
        <div class="links-grid">
          <a href="#" class="social-link douyin" title="抖音">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
              <path d="M19.5 3.5c-1.1 0-2 .9-2 2v.4c-1.3-.2-2.6-.8-3.7-1.7l-.8-.7v7.3c0 2.8-2.2 5-5 5s-5-2.2-5-5 2.2-5 5-5c.6 0 1.2.1 1.7.3V7.5c-2.2.5-3.8 2.5-3.8 4.8 0 2.8 2.2 5 5 5s5-2.2 5-5V5.5c0-1.1-.9-2-2-2zm-10.8 8c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2zm10.8-5c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z"/>
            </svg>
            <span>抖音</span>
          </a>
          
          <a href="#" class="social-link xiaohongshu" title="小红书">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
              <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15h-2v-6h2v6zm-1-7c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1zm5 7h-2v-6h2v6zm-1-7c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1z"/>
            </svg>
            <span>小红书</span>
          </a>
          
          <a href="#" class="social-link wechat" title="微信公众号">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
              <path d="M8.5 13.5c0-2.5 2-4.5 4.5-4.5s4.5 2 4.5 4.5-2 4.5-4.5 4.5-4.5-2-4.5-4.5zm-5 0c0-2.5 2-4.5 4.5-4.5s4.5 2 4.5 4.5-2 4.5-4.5 4.5-4.5-2-4.5-4.5zm10.5 0c0-2.5-2-4.5-4.5-4.5s-4.5 2-4.5 4.5 2 4.5 4.5 4.5 4.5-2 4.5-4.5-4.5z"/>
            </svg>
            <span>微信公众号</span>
          </a>
          
          <a href="#" class="social-link bilibili" title="哔哩哔哩">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
              <path d="M18.7 6.3c-.6-.6-1.6-.6-2.2 0l-1.4 1.4c-.6.6-.6 1.6 0 2.2l1.4 1.4c.6.6 1.6.6 2.2 0 .6-.6.6-1.6 0-2.2l-1.4-1.4c-.6-.6-1.6-.6-2.2 0zM6.5 6.3c-.6.6-1.6.6-2.2 0L2.9 7.7c-.6.6-.6 1.6 0 2.2l1.4 1.4c.6.6 1.6.6 2.2 0 .6-.6.6-1.6 0-2.2L4.3 7.7c-.6-.6-1.6-.6-2.2 0zM12 8c-2.2 0-4 1.8-4 4s1.8 4 4 4 4-1.8 4-4-1.8-4-4-4zm0 6c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z"/>
            </svg>
            <span>哔哩哔哩</span>
          </a>
        </div>
      </div>
      
      <div class="qr-code-section">
        <h4 class="section-title">扫码关注</h4>
        <div class="qr-code-wrapper">
          <div class="qr-code-placeholder">
            <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round">
              <rect x="3" y="3" width="7" height="7"></rect>
              <rect x="14" y="3" width="7" height="7"></rect>
              <rect x="14" y="14" width="7" height="7"></rect>
              <rect x="3" y="14" width="7" height="7"></rect>
              <rect x="7" y="7" width="3" height="3"></rect>
              <rect x="14" y="10" width="3" height="3"></rect>
              <rect x="10" y="14" width="3" height="3"></rect>
            </svg>
            <p class="qr-text">微信公众号二维码</p>
          </div>
        </div>
      </div>
      
      <div class="contact-info">
        <h4 class="section-title">联系我们</h4>
        <div class="contact-item">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path>
            <polyline points="22,6 12,13 2,6"></polyline>
          </svg>
          <span>contact@xiaoma.com</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.blog-profile-container {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
}

.profile-card {
  background-color: var(--color-bg-card);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-lg);
  padding: 1rem;
  box-shadow: var(--shadow-md);
  transition: all var(--transition-base) ease;
  height: 100%;
  overflow-y: auto;
}

.profile-card:hover {
  box-shadow: var(--shadow-lg);
}

.profile-header {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid var(--color-border);
}

.avatar {
  width: 64px;
  height: 64px;
  border-radius: var(--radius-full);
  background: var(--gradient-primary);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--color-white);
  margin-bottom: 0.75rem;
  box-shadow: var(--shadow-md);
}

.profile-name {
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--color-text-primary);
  margin: 0 0 0.25rem 0;
  letter-spacing: 0.3px;
}

.profile-title {
  font-size: 0.85rem;
  color: var(--color-text-secondary);
  margin: 0;
}

.profile-intro {
  margin-bottom: 1rem;
}

.intro-text {
  font-size: 0.85rem;
  line-height: 1.5;
  color: var(--color-text-secondary);
  margin: 0;
  text-align: justify;
}

.social-links {
  margin-bottom: 1rem;
}

.section-title {
  font-size: 0.9rem;
  font-weight: 600;
  color: var(--color-text-primary);
  margin: 0 0 0.75rem 0;
  padding-bottom: 0.4rem;
  border-bottom: 2px solid var(--color-border);
}

.links-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0.5rem;
}

.social-link {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 0.75rem;
  background-color: var(--color-bg-secondary);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-md);
  text-decoration: none;
  transition: all var(--transition-base) ease;
  color: var(--color-text-secondary);
}

.social-link:hover {
  background-color: var(--color-bg-tertiary);
  border-color: var(--color-primary);
  color: var(--color-primary);
  transform: translateY(-2px);
  box-shadow: var(--shadow-sm);
}

.social-link svg {
  margin-bottom: 0.35rem;
  transition: transform var(--transition-base) ease;
}

.social-link:hover svg {
  transform: scale(1.1);
}

.social-link span {
  font-size: 0.8rem;
  font-weight: 500;
}

.douyin:hover {
  border-color: #FE2C55;
  color: #FE2C55;
}

.xiaohongshu:hover {
  border-color: #FF2442;
  color: #FE2C55;
}

.wechat:hover {
  border-color: #07C160;
  color: #07C160;
}

.bilibili:hover {
  border-color: #00A1D6;
  color: #00A1D6;
}

.qr-code-section {
  margin-bottom: 1rem;
}

.qr-code-wrapper {
  display: flex;
  justify-content: center;
}

.qr-code-placeholder {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0.75rem;
  background-color: var(--color-bg-secondary);
  border: 1px solid var(--color-border);
  border-radius: var(--radius-md);
  transition: all var(--transition-base) ease;
}

.qr-code-placeholder:hover {
  border-color: var(--color-primary);
  box-shadow: var(--shadow-sm);
}

.qr-code-placeholder svg {
  color: var(--color-text-muted);
  margin-bottom: 0.35rem;
}

.qr-text {
  font-size: 0.75rem;
  color: var(--color-text-muted);
  margin: 0;
  text-align: center;
}

.contact-info {
  margin-bottom: 0;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.5rem;
  background-color: var(--color-bg-secondary);
  border-radius: var(--radius-md);
  color: var(--color-text-secondary);
  font-size: 0.85rem;
  transition: all var(--transition-base) ease;
}

.contact-item:hover {
  background-color: var(--color-bg-tertiary);
  color: var(--color-primary);
}

.contact-item svg {
  flex-shrink: 0;
  color: var(--color-text-muted);
  transition: color var(--transition-base) ease;
}

.contact-item:hover svg {
  color: var(--color-primary);
}

@media (max-width: 1200px) {
  .profile-card {
    width: 100%;
  }
}

@media (max-width: 1024px) {
  .profile-card {
    width: 100%;
  }
}

@media (max-width: 768px) {
  .profile-card {
    width: 100%;
    padding: 1.25rem;
  }
  
  .links-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 0.5rem;
  }
  
  .social-link {
    padding: 0.75rem;
  }
  
  .social-link span {
    font-size: 0.8rem;
  }
}

@media (max-width: 480px) {
  .profile-card {
    padding: 1rem;
  }
  
  .avatar {
    width: 64px;
    height: 64px;
  }
  
  .profile-name {
    font-size: 1.1rem;
  }
  
  .links-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 0.5rem;
  }
  
  .social-link {
    padding: 0.6rem;
  }
  
  .social-link svg {
    width: 20px;
    height: 20px;
  }
  
  .social-link span {
    font-size: 0.75rem;
  }
}
</style>