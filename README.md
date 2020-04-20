# Santos
<div id='collection-component-1587408778480'></div>
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
      domain: 'silverstar-sa-ja-cipele-shoe.myshopify.com',
      storefrontAccessToken: 'e9ac3ae1cbe96e538fcc150e95f0bbf8',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('collection', {
        id: '161292746855',
        node: document.getElementById('collection-component-1587408778480'),
        moneyFormat: '%E2%82%AC%7B%7Bamount_with_comma_separator%7D%7D%20EUR',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px",
          "width": "calc(25% - 20px)"
        },
        "img": {
          "height": "calc(100% - 15px)",
          "position": "absolute",
          "left": "0",
          "right": "0",
          "top": "0"
        },
        "imgWrapper": {
          "padding-top": "calc(75% + 15px)",
          "position": "relative",
          "height": "0"
        }
      },
      "title": {
        "font-size": "14px",
        "color": "#0f2bc9"
      },
      "button": {
        "font-family": "Droid Sans, sans-serif",
        "color": "#161818",
        ":hover": {
          "color": "#161818",
          "background-color": "#17cee1"
        },
        "background-color": "#19e5fa",
        ":focus": {
          "background-color": "#17cee1"
        },
        "border-radius": "38px"
      },
      "price": {
        "font-family": "Montserrat, sans-serif",
        "color": "#8f7777"
      },
      "compareAt": {
        "font-family": "Montserrat, sans-serif",
        "color": "#8f7777"
      },
      "unitPrice": {
        "font-family": "Montserrat, sans-serif",
        "color": "#8f7777"
      },
      "description": {
        "font-family": "Montserrat, sans-serif",
        "font-weight": "bold",
        "font-size": "17px",
        "color": "#534646"
      }
    },
    "buttonDestination": "modal",
    "contents": {
      "options": false
    },
    "text": {
      "button": "Produkt Anschauen"
    },
    "googleFonts": [
      "Montserrat",
      "Droid Sans"
    ]
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
        "font-family": "Droid Sans, sans-serif",
        "color": "#161818",
        ":hover": {
          "color": "#161818",
          "background-color": "#17cee1"
        },
        "background-color": "#19e5fa",
        ":focus": {
          "background-color": "#17cee1"
        },
        "border-radius": "38px"
      },
      "title": {
        "color": "#1536f4"
      },
      "price": {
        "font-family": "Arial, sans-serif",
        "font-size": "14px"
      },
      "compareAt": {
        "font-family": "Arial, sans-serif",
        "font-size": "11.9px"
      },
      "unitPrice": {
        "font-family": "Arial, sans-serif",
        "font-size": "11.9px"
      },
      "description": {
        "font-family": "Arial, sans-serif",
        "color": "#0d4971"
      }
    },
    "googleFonts": [
      "Droid Sans"
    ],
    "text": {
      "button": "In den Warenkorb legen"
    }
  },
  "modal": {
    "styles": {
      "modal": {
        "background-color": "#ecf4f2"
      }
    }
  },
  "cart": {
    "styles": {
      "button": {
        "font-family": "Droid Sans, sans-serif",
        "color": "#161818",
        ":hover": {
          "color": "#161818",
          "background-color": "#17cee1"
        },
        "background-color": "#19e5fa",
        ":focus": {
          "background-color": "#17cee1"
        },
        "border-radius": "38px"
      },
      "title": {
        "color": "#1e32e5"
      },
      "header": {
        "color": "#1e32e5"
      },
      "lineItems": {
        "color": "#1e32e5"
      },
      "subtotalText": {
        "color": "#1e32e5"
      },
      "subtotal": {
        "color": "#1e32e5"
      },
      "notice": {
        "color": "#1e32e5"
      },
      "currency": {
        "color": "#1e32e5"
      },
      "close": {
        "color": "#1e32e5",
        ":hover": {
          "color": "#1e32e5"
        }
      },
      "empty": {
        "color": "#1e32e5"
      },
      "noteDescription": {
        "color": "#1e32e5"
      },
      "discountText": {
        "color": "#1e32e5"
      },
      "discountIcon": {
        "fill": "#1e32e5"
      },
      "discountAmount": {
        "color": "#1e32e5"
      },
      "cart": {
        "background-color": "#eff2f8"
      },
      "footer": {
        "background-color": "#eff2f8"
      }
    },
    "text": {
      "title": "Wagenkorb",
      "total": "Subtotal",
      "empty": "Ihr Warenkorb ist leer.",
      "notice": "Versand- und Rabattcodes werden an der Kasse hinzugefügt.",
      "button": "Checkout",
      "noteDescription": "Besondere Anweisungen für den Verkäufer"
    },
    "contents": {
      "note": true
    },
    "googleFonts": [
      "Droid Sans"
    ]
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Droid Sans, sans-serif",
        "background-color": "#19e5fa",
        ":hover": {
          "background-color": "#17cee1"
        },
        ":focus": {
          "background-color": "#17cee1"
        }
      },
      "count": {
        "color": "#161818",
        ":hover": {
          "color": "#161818"
        }
      },
      "iconPath": {
        "fill": "#161818"
      }
    },
    "googleFonts": [
      "Droid Sans"
    ]
  },
  "lineItem": {
    "styles": {
      "variantTitle": {
        "color": "#1e32e5"
      },
      "title": {
        "color": "#1e32e5"
      },
      "price": {
        "color": "#1e32e5"
      },
      "fullPrice": {
        "color": "#1e32e5"
      },
      "discount": {
        "color": "#1e32e5"
      },
      "discountIcon": {
        "fill": "#1e32e5"
      },
      "quantity": {
        "color": "#1e32e5"
      },
      "quantityIncrement": {
        "color": "#1e32e5",
        "border-color": "#1e32e5"
      },
      "quantityDecrement": {
        "color": "#1e32e5",
        "border-color": "#1e32e5"
      },
      "quantityInput": {
        "color": "#1e32e5",
        "border-color": "#1e32e5"
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
