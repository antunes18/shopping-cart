<!-- svelte-ignore a11y-label-has-associated-control -->
<!-- svelte-ignore a11y-missing-attribute -->
<div class="navbar bg-base-100">
    <div class="flex-1">
      <a class="btn btn-ghost normal-case text-xl">Bem Vestido</a>
    </div>
    <div class="flex-none">
      <div class="dropdown dropdown-end">
        <label tabindex="0" class="btn btn-ghost btn-circle">
          <div class="indicator">
            <i class="bi bi-cart"></i>
            <span class="badge badge-sm indicator-item">0</span>
          </div>
        </label>
        <div tabindex="0" class="mt-3 card card-compact dropdown-content w-52 bg-base-100 shadow">
          <div class="card-body">
            <span class="font-bold text-lg">0 Itens</span>
            <span class="text-info">Total: R$ 0</span>
            <div class="card-actions">
              <button class="btn btn-primary btn-block">Ver carrinho</button>
            </div>
          </div>
        </div>
      </div>
    </div>
</div>