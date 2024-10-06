<template>
    <div class="all" id="contact">
      
      <footer class="footer">
        <h2 class="ftext">Renan Bick</h2>
        <p class="ftext">@{{time}}. All Rights Reserved</p>
        <div class="ftext">
          <a href="https://github.com/postrenan" target="_blank"><i class="fab fa-github" ></i></a>
          <a href="https://www.linkedin.com/in/renan-bick/" target="_blank"><i class="fab fa-linkedin"></i></a>
        </div>
      </footer>
    </div>
  </template>

<script setup>
const time = 2024;
</script>
  
  <style scoped>
  .all {
    display: flex;
    flex-direction: column;
  }
  
  .attention {
    color: var(--third-text);
  }
  
  .contact {
    color: var(--primary-text);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    gap: 30px;
    flex-wrap: wrap;
  }
  
  .left,
  .right {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .right{
    margin: 75px;
  }
  
  .left {
    flex: 1;
    min-width: 250px;
  }
  
  .text {
    color: var(--primary-text);
    font-size: 40px;
    font-weight: bolder;
    margin: 0 0 20px 75px;
  }
  
  .btn {
    color: var(--primary-text);
    padding: 10px 20px;
    max-width: 120px;
    color: var(--primary-text);
    border: solid 2px var(--primary-btn);
    background-color: var(--primary-btn);
    font-size: 18px;
    cursor: pointer;
    border-radius: 4px;
    transition: background-color 0.3s ease;
    margin: 0 0 20px 75px;

  }
  
  .btn:hover {
    background-color: var(--primary-text);
    color: var(--primary-bg);
  }
  
  .right {
    flex: 1;
    min-width: 250px;
    justify-content: flex-start;
  }
  
  input,
  textarea {
    display: block;
    width: 100%;
    padding: 12px;
    margin-bottom: 20px;
    font-size: 18px;
    border: 2px solid var(--primary-text);
    border-radius: 5px;
    background-color: #f9f9f9;
    color: var(--primary-text);
  }
  
  textarea {
    resize: vertical;
    min-height: 120px;
    max-height: 250px;
  }
  
  footer {
    color: var(--primary-text);
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 18px;
    background-color: var(--second-bg);
    padding: 40px 0;
    margin-top: 50px;
  }
  
  .ftext {
    margin: 10px 0;
    background-color: var(--second-bg);
  }
  
  .ftext a {
    background-color: var(--second-bg);
    border: none;
    font-size: 20px;
    color: var(--primary-text);
    cursor: pointer;
    margin: 0 10px;
    transition: transform 0.3s ease;
    
  }
  
  .ftext a:hover {
    transform: scale(1.2);
  }
  
  @media (max-width: 1024px) {
    .contact {
      flex-direction: column;
      align-items: center;
    }
  
    .left,
    .right {
      max-width: 90%;
    }
  
    .text {
      font-size: 28px;
      text-align: center;
    }
  
    .btn {
      font-size: 16px;
    }
  
    footer {
      font-size: 16px;
      padding: 20px 0;
    }
  }
  
  @media (max-width: 768px) {
    .text {
      font-size: 24px;
    }
  
    .btn {
      font-size: 14px;
      padding: 8px 16px;
    }
  
    input,
    textarea {
      font-size: 16px;
    }
  
    footer {
      font-size: 14px;
      padding: 20px 0;
    }
  }
  
  @media (max-width: 480px) {
    .text {
      font-size: 20px;
      text-align: center;
    }
  
    .btn {
      font-size: 14px;
      padding: 10px 15px;
    }
  
    input,
    textarea {
      font-size: 14px;
    }
  
    footer {
      font-size: 12px;
      padding: 10px 0;
    }
  
    .ftext a {
      font-size: 18px;
    }
  }
  </style>

  
  