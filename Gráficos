const obterCSS = (variavel) => {
    const estilosBody = getComputedStyle(document.body)
    return estilosBody.getPropertyValue(variavel)
}

const configuracaoTick = {
    familia: obterCSS('--font'),
    tamanho: 16,
    cor: obterCSS('--primary-color')
}

export {obterCSS, configuracaoTick}
