---
template: faq-page
path: /faq
title: FAQ
questions:
  - answer: >-
      tBTC связан с BTC общим предложением, а не ценой. Поэтому использование
      алгоритмических механизмов для обеспечения ценовой привязки не требуется.
    question: Как tBTC поддерживает свою привязку c BTC?
  - answer: >-
      tBTC и BTC не связаны между собой единой ценой, используется связка по
      предложению. Это значит, что отношение BTC/tBTC может принимать разное
      значение, а tBTC может торговаться с незначительным премиумом или
      дисконтом.
    question: Почему цена tBTC отличается от цены BTC?
  - answer: >-
      Потому что это делает систему более защищенной, что особенно важно в DeFi
      при запуске новой сети. ETH служит более надежным обеспечением потому, что
      является стандартом DeFi. При этом, команда, разрабатывающая tBTC,
      планирует изменить залоговое соотношение ETH/BTC из 150% до 135% вскоре
      после запуска. Так же рассматривается внедрение новых механизмов, которые
      спустя некоторое время смогут опустить это соотношение до 40%.
    question: Почему tBTC обеспечен токеном ETH в текущем соотношении?
  - answer: >-
      Технология tBTC является новой, поэтому невозможно предугадать каждый
      случай, в котором что-то может пойти не так. Надо сказать, что наше
      сообщество уже идентифицировало несколько таких ситуаций и приняло
      продуманные меры для их решения. Модель безопасности tBTC такова, что если
      подписанты вступят в сговор между собой и сбегут с биткоин-депозитом, то
      пострадавшим от этого пользователям будет выплачен tBTC; вот для чего
      существуют залоги ETH (они будут изъяты у мошенников и ликвидированы).
      Если же цена ETH значительно упадет за короткий промежуток времени и ВСЕ
      подписанты сбегут, одновременно разорвав привязку, то система станет
      синтетической. Для получения большей информации обратитесь к документу <a
      href="https://docs.keep.network/tbtc/index.pdf"
      target="_blank">"Техническая характеристика tBTC"</a>.
    question: Где в системе tBTC что-то может пойти не так?
  - answer: >-
      Слишком большое количество размеров лотов усложняет работу поставщикам
      ликвидности. Сохранение нескольких стандартных размеров лотов создает
      большую доступность для их выкупа.
    question: Почему размер лотов зафиксирован? Почему нельзя выбрать случайный номинал?
  - answer: >-
      Пока нет. Чтобы использовать данные об эмиссии и погашении tBTC в dapps
      нужно интегрироваться с сетью. Открытый исходный код в <a
      href="https://github.com/keep-network/tbtc.js" target="_blank"> [tbtc.js
      GitHub](https://github.com/keep-network/tbtc.js) </a> предоставляет
      возможность разработчикам строить интерфейсы, которые соответствуют их
      продуктам. Лучшим подходом для валидации биткоин-транзакций является
      запуск electrum-сервера, который легко “поднять”.
    question: >-
      Существует ли виджет, используя который я могу “вытаскивать” данные об
      эмиссии и погашении tBTC в мое Defi dapp?
  - answer: >-
      На данный момент, команда ConsenSys Diligence завершает шестинедельный
      аудит кода и криптографии tBTC. Мы опубликуем результаты, как только они
      станут доступными.
    question: Проводился ли аудит tBTC?
  - answer: >-
      Каждому пользователю следует провести собственный анализ того, существуют
      ли какие-либо легальные ограничения в его юрисдикции, препятствующие
      использование им tBTC или требующие от него регистрации в определенных
      госучреждениях.
    question: >-
      Считаюсь ли я лицом, предоставляющим финансовые услуги, если я занимаюсь
      стейкингом ETH и “подписыванием” в сети tBTC?
  - answer: >-
      Для того, чтобы определить является ли перевод BTC в tBTC налогооблагаемой
      операцией в вашей юрисдикции, обратитесь к соответствующему специалисту.
      Обратите внимание на не взаимозаменяемый токен (NFT), который
      ассоциируется с UTXO вашего депозита. NFT разработан для оплаты комиссии
      за хранение BTC и предоставления возможности “погашать” именно ваш UTXO в
      рамках шестимесячного периода.
    question: Облагается ли налогом конвертация BTC в tBTC?
  - answer: >-
      Группа подписантов сети tBTC использует пороговую подпись ECDSA, как
      замену мультисига Биткоина. Для каждого депозита случайным маячком (random
      beacon) выбирается группа подписантов, которая генерирует хэш публичного
      ключа (PKH) для вкладчика и записывает его в блокчейн Эфириума.
    question: Как группа подписантов tBTC может быть не кастодиальной?
  - answer: >-
      Группа из приблизительно 80-ти участников приватной продажи KEEP, а также
      нескольких других доверенных сторон, будут “подписывать” для tBTC сразу же
      после запуска проекта. Очень скоро мы анонсируем возможность участия в
      “подписании” путем стейкинга ETH для еще большего количества лиц.
    question: Кто такие подписанты? Может ли кто-угодно стать подписантом?
  - answer: >-
      Некоторые люди верят, что tBTC лучше по нескольким причинам. Есть проекты,
      которые разработали искусственные привязки цены, что не является истинным
      “мостом” между Эфириумом и Биткоином. Другие основаны на связывании
      предложения, но пользуются услугами централизованных сторон в процессе
      эмиссии и погашения и, поэтому, не являются цензуроустойчивыми системами.
      Некоторые новые “мосты” с привязкой предложения идут по пути
      децентрализации, но их модели безопасности менее устойчивы. Они полагаются
      на честность 2/3 сети, не взимают дополнительного залога для обеспечения
      депозитов и используют подход “разверни свою крипту”, вместо проверенной
      криптографии t-ECDSA.
    question: Чем tBTC лучше других “Биткоинов” на блокчейне Эфириума?
  - answer: >-
      Нет никакой необходимости в возврате ровно через 6 месяцев, кроме того
      случая, когда вы предпочитаете ”погасить” Биткоин используя определенный
      UTXO. Именно для этого используется депозитный токен tBTC (TDT). Однако,
      большинство ритейл пользователей DeFi не рассматривают этого, поэтому и не
      нуждаются в возврате через 6 месяцев.
    question: >-
      Что такое “комиссия за шестимесячный период”? Получается, что вернуть
      назад BTC можно только по истечении 6 месяцев?
  - answer: >-
      Твердых планов разработки “мостов” с другими блокчейнами у нас нет.
      Однако, [Cross-Chain Group](https://www.crosschain.group/) уже вели
      переговоры о построении “мостов”, не требующих к себе доверия, с Cosmos,
      Zcash, и Polkadot.
    question: Планируется ли разработка биткоин-мостов к другим блокчейнам?
  - answer: Нет.
    question: Предоставляет ли владение токеном tBTC какое-либо право управления?
  - answer: >-
      Команда, стоящая за tBTC, разрабатывает привязку по предложению, а не
      синтетический механизм привязки по цене. Для держателей биткоина важна не
      актуальная цена tBTC, а то, что его можно погасить за 1 BTC.
    question: Почему бы просто не сделать привязку по цене?
  - answer: >-
      Так как tBTC - это сайдчейн, которым пользуются анонимные стороны, то для
      предотвращения их возможного заговора с них взимается залог. На данный
      момент важно обеспечить взимание залога с подписантов, чтобы защитить
      пользователей от потенциальных нарушений. Оракул цены требуется для того,
      чтобы сохранять соотношение BTC/ETH для этого залога.
    question: Тогда почему tBTC нуждается в оракулах цены?
---
