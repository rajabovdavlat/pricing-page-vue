<!-- Pricing.vue -->
<template>
  <div class="container">
    <!-- Hero / Заголовок -->
    <div class="hero__first">
      <h2 class="hero__title">Unlock full access</h2>
      <p class="hero__desc">
        Upgrade to remove limits and access all premium features.
      </p>
    </div>

    <!-- Карточки планов -->
    <div class="hero__card-warpp">
      <!-- Starter / Free -->
      <div class="hero__card">
        <div class="card__top">
          <p class="card-desc">
            <span class="card__title">Starter</span> - Get Started & Explore
          </p>
          <img
            class="card__img"
            src="../public/img/svg/Frame1.svg"
            alt="flag"
          />
        </div>

        <div class="card__price">
          <p class="price__year"><span class="price">$0</span> /year</p>
        </div>

        <div class="best__for">
          <p class="best__desc">
            <span class="best__title">Best for:</span> Companies exploring the
            platform and market opportunities.
          </p>
          <button class="card__btn">Current Plan</button>
        </div>

        <div class="card__main">
          <h3 class="card__main-title">Why Choose Starter:</h3>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Quick enrollment</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Basic company profile</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">
              Market discovery with limited random access
            </p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">My Page enabled</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">
              Showcase up to 10 products or services
            </p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Limited Project Intelligence</p>
          </div>
        </div>

        <div class="card__dop-info">
          <p class="card__dop-desc">
            👉 Choose Starter if you want access to market insights while still
            validating the platform's value.
          </p>
        </div>
      </div>

      <!-- Pro -->
      <div class="hero__card">
        <div class="card__top">
          <p class="card-desc">
            <span class="card__title">Pro</span> - Grow & Compete
          </p>
          <img
            class="card__img"
            src="../public/img/svg/Frame2.svg"
            alt="flag"
          />
        </div>

        <div class="card__price">
          <p class="price__year"><span class="price">$3999</span> /year</p>
        </div>

        <div class="best__for">
          <p class="best__desc">
            <span class="best__title">Best for:</span> Companies ready to
            participate, promote, and win projects.
          </p>
          <button class="card__btn2">Upgrade to Pro</button>
        </div>

        <div class="card__main">
          <h3 class="card__main-title">Everything in Starter, and:</h3>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">
              Unlimited projects intelligence and insights
            </p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Any one country by your selection</p>
          </div>
          <!-- остальные пункты Pro ... -->
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">
              Tenders/RFQs from the selected country
            </p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Assistance up to 25 key contacts</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Reward Club benefits</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Business verification support</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Master account</p>
          </div>
        </div>

        <div class="card__dop-info">
          <p class="card__dop-desc">
            👉 Choose Pro if you want to actively compete, generate leads, and
            grow visibility without enterprise overhead.
          </p>
        </div>
      </div>

      <!-- Enterprise -->
      <div class="hero__card">
        <div class="card__top">
          <p class="card-desc">
            <span class="card__title">Enterprise</span> - Scale & Dominate
          </p>
          <img
            class="card__img"
            src="../public/img/svg/Frame3.svg"
            alt="flag"
          />
        </div>

        <div class="card__price">
          <p class="price__year"><span class="price">$6888</span> /year</p>
        </div>

        <div class="best__for">
          <p class="best__desc">
            <span class="best__title">Best for:</span> Companies managing
            multiple markets and high volume projects
          </p>
          <button class="card__btn3">Upgrade to Enterprise</button>
        </div>

        <div class="card__main">
          <h3 class="card__main-title">Everything in Pro, and:</h3>
          <!-- здесь добавляешь остальные пункты Enterprise аналогично -->
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Enhanced company profile</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">
              Multi Country access up to 5 countries
            </p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">
              Showcase up to 30 products or services
            </p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">
              Tenders/RFQs from the selected countries
            </p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Assistance up to 50 key contacts</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Master account & 2 sub-accounts</p>
          </div>
          <div class="card__main-info">
            <img src="../public/img/svg/galochka.svg" alt="" />
            <p class="card__main-desc">Dedicated relationship manager</p>
          </div>
          <!-- ... остальные ... -->
        </div>

        <div class="card__dop-info">
          <p class="card__dop-desc">
            👉 Choose Enterprise if you need to scale limitless, win deals and
            grow profitability
          </p>
        </div>
      </div>
    </div>

    <!-- Таблица сравнения (можно оставить как есть или вынести в компонент) -->
    <div class="comparison-table">
      <table>
        <thead>
          <tr>
            <th>Features</th>
            <th class="plan free">Free</th>
            <th class="plan pro">Pro</th>
            <th class="plan enterprise">Enterprise</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Enrollment</td>
            <td><img src="../public/img/svg/galochhka.svg" alt="" /></td>
            <td><img src="../public/img/svg/galochhka.svg" alt="" /></td>
            <td><img src="../public/img/svg/galochhka.svg" alt="" /></td>
          </tr>
          <tr>
            <td>Company Profile</td>
            <td>Basic</td>
            <td>Enhanced</td>
            <td>Enhanced</td>
          </tr>
          <tr>
            <td>Market Access</td>
            <td>Limited Random Access</td>
            <td>1</td>
            <td>5</td>
          </tr>
          <tr>
            <td>Project Intelligence</td>
            <td>8</td>
            <td>Unlimited</td>
            <td>Unlimited</td>
          </tr>
          <tr>
                <td>My Page</td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
              </tr>
              <!-- ... остальные строки ... -->
              <tr>
                <td>Product Showcase</td>
                <td>10</td>
                <td>10</td>
                <td>30</td>
              </tr>
                <tr>
                <td>Key Words Trends</td>
                <td><img src="../public/img/svg/x.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
              </tr>
              <tr>
                <td>Tender / RFQ</td>
                <td><img src="../public/img/svg/x.svg" alt=""></td>
                <td>Min. 120/year</td>
                <td>Min. 250/Year</td>
              </tr>
              <!-- ... остальные строки ... -->
              <tr>
                <td>Assistance</td>
                <td><img src="../public/img/svg/x.svg" alt=""></td>
                <td>25/Year</td>
                <td>50/Year</td>
                </tr>
                  <tr>
                <td>Rewards Club</td>
                <td><img src="../public/img/svg/x.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
              </tr>
              <tr>
                <td>Account</td>
                <td>1</td>
                <td>1</td>
                <td>3</td>
              </tr>
              <!-- ... остальные строки ... -->
              <tr>
                <td>Business Verification Support</td>
                <td><img src="../public/img/svg/x.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
                </tr>
                  <tr>
                <td>Customer Service</td>
                <td>Standard</td>
                <td>Basic</td>
                <td>Personalized</td>
              </tr>
              <tr>
                <td>Relationship Manager</td>
                <td><img src="../public/img/svg/x.svg" alt=""></td>
                <td><img src="../public/img/svg/x.svg" alt=""></td>
                <td><img src="../public/img/svg/galochhka.svg" alt=""></td>
                </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style scoped>
/* Hero section */
.hero__first {
  margin-bottom: 16px;
}

.hero__title {
  font-weight: 500;
  font-size: 1.25rem;
  line-height: 1;
  margin-bottom: 0.375rem;
  color: #333333;
}

.hero__desc {
  font-weight: 400;
  font-size: 1rem;
  color: #333333;
}

.hero__card-warpp {
  display: flex;
  gap: 32px;
  justify-content: center;
  /* align-items: stretch;  */
}

.hero__card {
  width: 100%;
  max-width: 384px;
  border: 1px solid #f59f0a;
  border-radius: 16px;
  padding: 32px 40px 0 24px;
  display: flex;
  flex-direction: column;
  box-shadow: 0px 10px 7px 0px rgba(0, 0, 0, 0.2);
  background-color: rgba(249, 248, 246, 1);
}

.card__top {
  display: flex;
  position: relative;
}

.card__img {
  margin-top: -33px;
  margin-right: -26px;
  flex-shrink: 0;
  object-fit: contain;
}

.card__title {
  font-weight: 500;
  color: #333333;
  font-size: 1.25rem;
  font-weight: 600;
}

.card-desc {
  color: #333333;
  font-weight: 400;
  font-size: 0.75rem;
  white-space: nowrap;
  text-overflow: ellipsis;
  flex: 1;
}

.card__price {
  margin-bottom: 9px;
}
.price {
  color: #333333;
  font-weight: 600;
  font-size: 24px;
}

.price__year {
  font-weight: 400;
  font-size: 12px;
  color: #737373;
}
.best__for {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 4px;
  width: 100%;
  max-width: 318px;
  margin-bottom: 24px;
}

.best__title {
  color: #f59f0a;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  white-space: nowrap;
  flex-shrink: 0;
}

.best__desc {
  color: #737373;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  flex: 1;
  margin-bottom: 0.75rem;
}

.card__main-title {
  font-weight: 500;
  font-size: 12px;
  color: #333333;
  margin-bottom: 6px;
}

.card__main-info {
  display: flex;
  align-items: flex-start;
  gap: 8px;
}

.card__main-desc {
  color: #737373;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  margin-bottom: 8px;
}

.card__dop-info {
  margin-top: 40px;
  /* margin-bottom: 40px; */
}
.card__dop-desc {
  color: #737373;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  margin-bottom: 16px;
}
.card__btn {
  padding: 10px 105px;
  min-height: 48px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  width: 100%;
  color: #0d0d0d;
  font-weight: 500;
  font-size: 12px;
  background-color: #f59f0a;
  border-radius: 4px;
  border: none;
  cursor: pointer;

  margin-top: auto;
  align-self: center;
  transition: background-color 0.12s ease;
}

.card__btn:active {
  background-color: #dbdad6;
}

.card__btn2 {
  padding: 11px 95px;
  min-height: 48px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  width: 100%;
  color: #0d0d0d;
  font-weight: 500;
  font-size: 12px;
  background-color: #f59f0a;
  border-radius: 4px;
  border: none;
  cursor: pointer;

  margin-top: auto;
  align-self: center;
  transition: background-color 0.12s ease;
}

.card__btn2:active {
  background-color: #dbdad6;
}
.card__btn3 {
  padding: 11px 68px;
  min-height: 48px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  width: 100%;
  color: #0d0d0d;
  font-weight: 500;
  font-size: 12px;
  background-color: #f59f0a;
  border-radius: 4px;
  border: none;
  cursor: pointer;

  margin-top: auto;
  align-self: center;
  transition: background-color 0.12s ease;
}

.card__btn3:active {
  background-color: #dbdad6;
}

.comparison-table {
  margin: 64px 0;
  overflow-x: auto;
  background: rgba(245, 159, 10, 0.05);
  border-radius: 16px;
  border: 1px solid rgba(224, 222, 215, 1);
}

.comparison-table table {
  width: 100%;
  border-collapse: collapse;
  background: #fff;
  color: #333333;
}

.comparison-table th,
.comparison-table td {
  padding: 16px;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  text-align: center;
  border-bottom: 1px solid rgba(224, 222, 215, 1);
  vertical-align: middle;
  background: rgba(249, 248, 246, 1);
}

/* Общие стили для всех заголовков таблицы (thead th) */
.comparison-table thead th {
  font-weight: 500;
  font-size: 14px;
  position: sticky;
  top: 0;
  z-index: 10;
  border-bottom: 2px solid rgba(224, 222, 215, 1);
}

/* Первая колонка (Features) — sticky слева */
.comparison-table th:first-child,
.comparison-table td:first-child {
  text-align: left;
  background: rgba(249, 248, 246, 1);
  color: #333333;
  position: sticky;
  left: 0;
  z-index: 5; /* ниже, чем top sticky */
}

/* Только заголовок Features (первая ячейка шапки) */
.comparison-table th:first-child {
  color: #333333;
  font-weight: 500;
  font-size: 14px;
  z-index: 11; /* выше, чем другие th */
}

/* Free — белый цвет */
.comparison-table thead th:nth-child(2) {
  color: #333333;
}

/* Pro — оранжевый цвет */
.comparison-table thead th:nth-child(3) {
  color: #f59f0a;
}

/* Тело таблицы: первая колонка (названия фич) */
.comparison-table td:first-child {
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
}

/* Лёгкое выделение колонки Pro */
.comparison-table td:nth-child(3) {
  background: #f59f0a0d;
}

/* Убираем нижнюю границу у последней строки */
.comparison-table tr:last-child td {
  border-bottom: none;
}
</style>
