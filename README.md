<div id='collection-component-1752012135277'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: '3b8b0b-34.myshopify.com',
      storefrontAccessToken: '4f1b73a1c1d93cf81a91b929d65cb0d1',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('collection', {
        id: '484842897690',
        node: document.getElementById('collection-component-1752012135277'),
        moneyFormat: 'Dhs.%20%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px",
          "width": "calc(25% - 20px)"
        }
      },
      "button": {
        ":hover": {
          "background-color": "#30352c"
        },
        "background-color": "#1c1f1a",
        ":focus": {
          "background-color": "#30352c"
        },
        "border-radius": "40px"
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        ":hover": {
          "background-color": "#30352c"
        },
        "background-color": "#1c1f1a",
        ":focus": {
          "background-color": "#30352c"
        },
        "border-radius": "40px"
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "option": {},
  "cart": {
    "styles": {
      "button": {
        ":hover": {
          "background-color": "#30352c"
        },
        "background-color": "#1c1f1a",
        ":focus": {
          "background-color": "#30352c"
        },
        "border-radius": "40px"
      },
      "title": {
        "color": "#3a3535"
      },
      "header": {
        "color": "#3a3535"
      },
      "lineItems": {
        "color": "#3a3535"
      },
      "subtotalText": {
        "color": "#3a3535"
      },
      "subtotal": {
        "color": "#3a3535"
      },
      "notice": {
        "color": "#3a3535"
      },
      "currency": {
        "color": "#3a3535"
      },
      "close": {
        "color": "#3a3535",
        ":hover": {
          "color": "#3a3535"
        }
      },
      "empty": {
        "color": "#3a3535"
      },
      "noteDescription": {
        "color": "#3a3535"
      },
      "discountText": {
        "color": "#3a3535"
      },
      "discountIcon": {
        "fill": "#3a3535"
      },
      "discountAmount": {
        "color": "#3a3535"
      }
    },
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    },
    "popup": false
  },
  "toggle": {
    "styles": {
      "toggle": {
        "background-color": "#1c1f1a",
        ":hover": {
          "background-color": "#30352c"
        },
        ":focus": {
          "background-color": "#30352c"
        }
      }
    }
  },
  "lineItem": {
    "styles": {
      "variantTitle": {
        "color": "#3a3535"
      },
      "title": {
        "color": "#3a3535"
      },
      "price": {
        "color": "#3a3535"
      },
      "fullPrice": {
        "color": "#3a3535"
      },
      "discount": {
        "color": "#3a3535"
      },
      "discountIcon": {
        "fill": "#3a3535"
      },
      "quantity": {
        "color": "#3a3535"
      },
      "quantityIncrement": {
        "color": "#3a3535",
        "border-color": "#3a3535"
      },
      "quantityDecrement": {
        "color": "#3a3535",
        "border-color": "#3a3535"
      },
      "quantityInput": {
        "color": "#3a3535",
        "border-color": "#3a3535"
      }
    }
  }
},
      });
    });
  }
})();
/*]]>*/
</script>
